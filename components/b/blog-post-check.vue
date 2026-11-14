<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iih-c_bzy"/><path class="qf3lwg-0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blog-post-check" /></template>
<style>
.iih-c_bzy {
  d: path("M14.3 21.5H3.5v-19h16v10.8m0 7.9v.3h-.3");
}

.qf3lwg-0y {
  d: path("M6.5 5.5h10V11h-10Zm0 9h5m-5 3.5H10m4.75 0l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
