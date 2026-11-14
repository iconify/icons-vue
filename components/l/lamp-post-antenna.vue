<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yz3lkq7wi"/><path class="bew789bhi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lamp-post-antenna" /></template>
<style>
.bew789bhi {
  d: path("M13 14.5a3 3 0 0 1 6 0ZM11.5 3a3.25 3.25 0 0 1 0 4m-5 0a3.25 3.25 0 0 1 0-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yz3lkq7wi {
  d: path("M9 21.5V5M6 21.5h6m-3-11h7v1");
}

</style>
