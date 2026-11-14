<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pmslefgki"/><path class="sp0tkrb8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:classroom-kids" /></template>
<style>
.pmslefgki {
  d: path("M13.3 16.5H2.5V4h19v8.5m-18 7h8.4");
}

.sp0tkrb8g {
  d: path("M6.5 11c1.5-3.5 3-3.5 3.5-1s2 2.5 3.5-1m2.5 6.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
