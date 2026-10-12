<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ekfjygb_w"/><path class="j9cvnk96j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:list-check-sharp" /></template>
<style>
.ekfjygb_w {
  d: path("M9.75 5.25h10.5m-10.5 7h10.5m-10.5 7h10.5m-17.5-16h4v4h-4zm0 7h4v4h-4zm0 7h4v4h-4z");
}

.j9cvnk96j {
  d: path("m3.85 5.35l.8.8l1.3-1.6m-2.1 7.8l.8.8l1.3-1.6");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
