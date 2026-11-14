<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0sys9n1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hotel-manager" /></template>
<style>
.s0sys9n1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 7a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM3.5 21.5q0-.184.009-.368t.027-.367t.045-.365q.027-.183.063-.363q.036-.181.081-.359q.045-.179.098-.355t.115-.35q.062-.173.133-.343q.07-.17.149-.337q.079-.166.166-.328q.086-.163.181-.321t.197-.311t.212-.301t.226-.29t.241-.279q.124-.136.254-.266t.266-.254q.137-.124.279-.241t.29-.226t.301-.212t.311-.197t.321-.181t.328-.166q.167-.079.337-.149q.17-.071.343-.133t.35-.115t.355-.098t.359-.081t.363-.063t.365-.045t.367-.027T11 14q.334 0 .666.03M17.75 14l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

</style>
