<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j5yxt517o"/><path class="dcwqhs41b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:circuit-breaker" /></template>
<style>
.dcwqhs41b {
  d: path("M9.25 12h5.5v6h-5.5Z");
}

.j5yxt517o {
  d: path("M3.5 2.5h17v19h-17Zm8.5 4V12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
