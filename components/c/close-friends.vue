<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9pag0b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:close-friends" /></template>
<style>
.t9pag0b4r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m8.803 3.203l.532 1.08q.174.352.564.409l1.192.173q1.066.154 1.399 1.179t-.439 1.777l-.861.841q-.283.275-.217.664l.204 1.186q.183 1.062-.69 1.696q-.872.633-1.826.131l-1.064-.56q-.349-.184-.698 0l-1.065.56q-.953.502-1.825-.131q-.873-.634-.69-1.696l.204-1.187q.066-.388-.216-.663l-.863-.841q-.771-.752-.438-1.777t1.399-1.179l1.191-.173q.391-.057.566-.41l.531-1.079q.476-.968 1.555-.968t1.555.968");
}

</style>
