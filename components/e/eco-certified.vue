<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ajl-qabzo"/><path class="g7ek8qcob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eco-certified" /></template>
<style>
.ajl-qabzo {
  d: path("m12.68 3.34l.65.58q.68.59 1.56.42l.85-.17q.89-.18 1.17.67l.28.83q.29.85 1.14 1.14l.83.28q.85.29.67 1.17l-.17.85q-.17.88.42 1.56l.58.65q.59.68 0 1.36l-.58.65q-.59.68-.42 1.56l.17.85q.18.89-.67 1.17l-.83.28q-.85.29-1.14 1.14l-.28.83q-.28.85-1.17.67l-.85-.17q-.88-.17-1.56.42l-.65.58q-.68.59-1.36 0l-.65-.58q-.68-.59-1.56-.42l-.85.17q-.88.18-1.17-.67l-.28-.83q-.29-.85-1.14-1.14l-.83-.28q-.85-.28-.67-1.17l.17-.85q.17-.88-.42-1.56l-.58-.65q-.59-.68 0-1.36l.58-.65q.59-.68.42-1.56l-.17-.85q-.18-.89.67-1.17l.83-.28q.85-.29 1.14-1.14l.28-.83q.28-.85 1.17-.67l.85.17q.88.17 1.56-.42l.65-.58q.68-.59 1.36 0");
}

.g7ek8qcob {
  d: path("M8.5 15.5c.25-4 2.25-6.25 7-7c-.25 4-2.25 6.25-7 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
