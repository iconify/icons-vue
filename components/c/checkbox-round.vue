<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vni3pi4oq"/><path class="zr7bvmb3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:checkbox-round" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vni3pi4oq {
  d: path("M2.5 12a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.zr7bvmb3q {
  d: path("M5.25 12.25L7 14l2.75-3.5M16 12h5.5");
}

</style>
