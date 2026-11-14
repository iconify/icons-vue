<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mkq9rn5pb"/><path class="m1rj8hvhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:last-mile" /></template>
<style>
.m1rj8hvhe {
  d: path("M15.75 21.5V18h3v3.5m-1.5-13.25s-2.5-1.75-2.5-3.75a2.5 2.5 0 0 1 5 0c0 2-2.5 3.75-2.5 3.75ZM2.5 21.5h3m2.75 0h2");
}

.mkq9rn5pb {
  d: path("m13 15l4.25-4l4.25 4v6.5H13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
