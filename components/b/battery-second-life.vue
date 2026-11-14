<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ledfv3f5u"/><path class="is8nqnbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:battery-second-life" /></template>
<style>
.is8nqnbzt {
  d: path("M16.75 14.5L18 15.75L16.75 17");
}

.ledfv3f5u {
  d: path("M13 16H2.5V4.5h16v7.8M21 8.75v3m-.25 6.75A2.75 2.75 0 1 1 18 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
