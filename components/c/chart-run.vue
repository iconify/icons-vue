<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="noj4z5n_b"/><path class="fro2oab9b"/><path class="bt7k5muij"/><path class="a-3b19bon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-run" /></template>
<style>
.a-3b19bon {
  d: path("M19.25 17a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.bt7k5muij {
  fill: currentColor;
  d: path("M6.5 8.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4.5-2a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM15.5 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.fro2oab9b {
  d: path("M2.25 16.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.noj4z5n_b {
  d: path("m3.5 16.5l4.5-8l4.5-2L17 9l3.5 8m-18-4.5h2m2 0h2m2 0h2m2 0h2m2 0h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
