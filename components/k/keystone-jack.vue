<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d4for3r-x"/><path class="g3uovdayt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:keystone-jack" /></template>
<style>
.d4for3r-x {
  d: path("m3 7l3-3h12l3 3v13H3Zm0 0h18");
}

.g3uovdayt {
  d: path("M7.5 10h9v5h-2v2h-5v-2h-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
