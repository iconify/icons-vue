<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vn-_embwu"/><path class="fu-egrozj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-axes" /></template>
<style>
.fu-egrozj {
  d: path("m2.5 5.5l2-2l2 2m12 12l2 2l-2 2m-8.5-2V17m5.5 2.5V17m-11-7.5H7m-2.5 5H7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vn-_embwu {
  d: path("M4.5 3.5v16h16");
}

</style>
