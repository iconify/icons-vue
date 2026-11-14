<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acr34gbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:author-follow" /></template>
<style>
.acr34gbcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 7a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M3 21q0-.184.009-.368t.027-.367t.045-.365q.027-.183.063-.363q.036-.181.081-.359q.045-.179.098-.355t.115-.35q.062-.173.133-.343q.07-.17.149-.337q.079-.166.166-.328q.086-.163.181-.321t.197-.311t.212-.301t.226-.29q.117-.142.241-.279q.124-.136.254-.266t.266-.254q.137-.124.279-.241t.29-.226t.301-.212t.311-.197t.321-.181t.328-.166q.167-.079.337-.149q.17-.071.343-.133t.35-.115t.355-.098t.359-.081t.363-.063t.365-.045t.367-.027t.368-.009q.641 0 1.273.109t1.236.323t1.164.529t1.057.718M18 15v6m-3-3h6");
}

</style>
