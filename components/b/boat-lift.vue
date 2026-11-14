<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xwlcmyxvb"/><path class="ydao2826v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boat-lift" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xwlcmyxvb {
  d: path("M3.5 21V3.5h17V21");
}

.ydao2826v {
  d: path("M12 3.5v6M7.5 13L12 9.5l4.5 3.5m-10 0h11l-1.75 4.5h-7.5Z");
}

</style>
