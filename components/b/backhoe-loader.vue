<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="im_1lxb4u"/><path class="dxskyvovj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:backhoe-loader" /></template>
<style>
.dxskyvovj {
  d: path("M6.25 17.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm7 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm4.25-5.25l2-2h2V6l-3 1.5m-12 3l-2-6l-2 6.5l1 3");
}

.im_1lxb4u {
  d: path("M6.5 15.5v-5H9V5h5v5.5h3.5v5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
