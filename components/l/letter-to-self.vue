<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d_vcnnbnq"/><path class="suwwq6z_v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:letter-to-self" /></template>
<style>
.d_vcnnbnq {
  d: path("M4.5 4h13a2 2 0 0 1 2 2v5.5H14l-3 5v.5H4.5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2Z");
}

.suwwq6z_v {
  d: path("m6 7.5l5 3.5l5-3.5m2 13s-2.75-1.75-2.75-3.5c0-.75.75-1.5 1.5-1.5c.5 0 1 .5 1.25.75c.25-.25.75-.75 1.25-.75c.75 0 1.5.75 1.5 1.5c0 1.75-2.75 3.5-2.75 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
