<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aejlgjbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alarm-clock-off" /></template>
<style>
.aejlgjbhj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.408 9.424q-.447.823-.678 1.731q-.23.908-.23 1.845q0 .184.009.368t.027.367t.045.365t.063.363t.081.359t.098.355t.115.35t.133.343t.149.337q.079.166.166.328q.086.163.181.321t.197.311t.212.301t.226.29t.241.279q.124.136.254.266t.266.254q.137.124.279.241t.29.226t.301.212t.311.197t.321.181t.328.166q.167.079.337.149q.17.071.343.133t.35.115t.355.098t.359.081t.363.063t.365.045t.367.027t.368.009q.476 0 .948-.06t.933-.18q.461-.119.903-.296q.442-.176.858-.408m3.539-4.391Q19.5 14.106 19.5 13q0-.184-.009-.368t-.027-.367t-.045-.365t-.063-.363t-.081-.359t-.098-.355t-.115-.35t-.133-.343t-.149-.337q-.079-.166-.166-.328q-.086-.163-.181-.321t-.197-.311t-.212-.301t-.226-.29q-.117-.142-.241-.279q-.124-.136-.254-.266t-.266-.254t-.279-.241t-.29-.226t-.301-.212t-.311-.197t-.321-.181q-.162-.087-.328-.166q-.167-.079-.337-.149q-.17-.071-.343-.133t-.35-.115t-.355-.098t-.359-.081t-.363-.063t-.365-.045t-.367-.027T12 5.5q-1.146 0-2.24.342M21 6l-3-3M6.5 18.5l-2 2m-1-17l17 17");
}

</style>
