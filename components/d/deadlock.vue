<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zrlhvtb3a"/><path class="cllxm0byq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deadlock" /></template>
<style>
.cllxm0byq {
  d: path("M10 10.5V7a4 4 0 0 1 8 0v3.5m-6 4v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zrlhvtb3a {
  d: path("M3.5 10.5h17v11h-17Zm2.5 0V7a4 4 0 0 1 8 0v3.5");
}

</style>
