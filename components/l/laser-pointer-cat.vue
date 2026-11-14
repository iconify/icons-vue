<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpi3n5bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:laser-pointer-cat" /></template>
<style>
.qpi3n5bhl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.659 17.878q-.494.391-1.046.694q-.552.304-1.147.511q-.594.207-1.215.312T10 19.5q-.184 0-.368-.009t-.367-.027t-.365-.045t-.363-.063t-.359-.081t-.355-.098t-.35-.115t-.343-.133t-.337-.149q-.166-.079-.328-.166q-.163-.086-.321-.181t-.311-.197t-.301-.212t-.29-.226q-.142-.117-.279-.241q-.136-.124-.266-.254t-.254-.266t-.241-.279t-.226-.29t-.212-.301t-.197-.311t-.181-.321q-.087-.162-.166-.328q-.079-.167-.149-.337q-.071-.17-.133-.343t-.115-.35t-.098-.355t-.081-.359t-.063-.363t-.045-.365t-.027-.367T2.5 12V3l4.75 3.5h5.5L17.5 3v9q0 .806-.171 1.593t-.506 1.52M7.5 12h.01m4.99 0h.01m9.24 2.5l-1.5 2.5m-3 2.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
