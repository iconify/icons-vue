<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oh350n3eh"/><path class="f15d-ccoo"/><path class="dxazypbqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anticline" /></template>
<style>
.dxazypbqx {
  d: path("M10.5 19.5c0-9 3-9 3 0m-11 0h19");
}

.f15d-ccoo {
  d: path("M6.5 19.5c0-14.5 11-14.5 11 0");
}

.oh350n3eh {
  d: path("M2.5 19.5c0-19.5 19-19.5 19 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
