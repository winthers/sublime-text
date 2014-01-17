
# Sublime Text Snippets



* Backbone 

	* [Model](#model):  **bm**
	* [Collection](#collection):  **bc**

* Marionette 

	* [ItemView](#itemview):  **miv**
	* [CollectionView](#collectionview):  **mclv**
	* [CompositeView](#compositeview):  **mcov**
	* [Layout](#layout):  **ml**

* Under score snippets. 

	* [Generic pattern](#generic-pattern):   **_** 

* Javascript

	* [Object function](#object-function): 	**of**
	* [Object hash](#object-hash):  		**oh**
	* [Key Value](#Key-Value): 				**kv**
	* [variable value](#variable-value): 	**vv**
	* [Function](#function): 				**fun**
	* [Class](#class): 						**class**


## Backbone 

#### Model
trigger **bm**

```js
var name = Backbone.Model.extend({})
```

#### Collection
trigger **bc**
```js
var name = Backbone.Collection.extend({})
```
## Marionette 

#### ItemView
trigger **miv**

```js
var name = Marionette.ItemView.extend({
	template: "template"
})
```


#### CollectionView
trigger **mclv**

```js
var name = Marionette.CollectionView.extend({
	itemView: itemView
})
```

#### CompositeView
trigger **mcov**

```js
var name = Marionette.CompositeView.extend({
	template: "template",
	itemView: itemView,
	itemViewContainer: "selector",

})
```

#### Layout

trigger: **ml**

```js
var name = Marionette.Layout.extend({
	template: "template",
	regions: {
		
	}
})
```




## Under score snippets. 

#### Generic pattern

trigger  **_**
```js
_.name(data, function(args){
	return 
})
```

@ extproto

```js
_.extend(Object.prototype, {

})
```

## Javascript

#### Object Function
trigger **of**

```js
name: function(args) {
	//body
},
```
#### Object hash

trigger **oh**

```js
key: {
	key: value,
},
```

#### Key Value
trigger **kv**

```js
key: value,
```

#### variable value
trigger **vv**

```js
var name = value;
```
#### function
trigger **fun**
```js
function name (args) {
	return 	
}
```
#### class
trigger **class**

Relies on underscore for the _.extend

```js
function name (options) {

}

_.extend(name.prototype, {
	
})

```
