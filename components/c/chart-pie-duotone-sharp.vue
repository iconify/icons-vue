<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sewq2pj7s"/><path class="c3ihy8bey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-pie-duotone-sharp" /></template>
<style>
.c3ihy8bey {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0m9-9v9h9m-9 0l6 6");
}

.ft5dv1b6b {
  fill: none;
}

.sewq2pj7s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 2.049V13h.586l6.743 6.744A10 10 0 0 1 2.26 9.735A10 10 0 0 1 11 2.049M13 11V2.049A10.01 10.01 0 0 1 21.951 11Zm1.414 2h7.537a10 10 0 0 1-2.207 5.329Z");
}

</style>
