<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvtsw44zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cold-snap-sharp" /></template>
<style>
.qvtsw44zn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 14.6V3h4v11.6a3.25 3.25 0 1 1-4 0Zm11.75-7.1v9m3.9-6.75l-7.8 4.5m7.8 0l-7.8-4.5m4.55.35l-.65-.89l-.65.89m2.62 1.51l.45-1l-1.1-.12m0 3.02l1.1-.12l-.45-1M16.1 13.9l.65.89l.65-.89m-2.62-1.51l-.45 1.01l1.1.11m0-3.02l-1.1.12l.45 1");
}

</style>
