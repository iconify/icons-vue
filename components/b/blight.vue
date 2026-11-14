<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wazfu6i_q"/><path class="nn8ns_lwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blight" /></template>
<style>
.nn8ns_lwo {
  d: path("M9.25 12.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm4-4a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wazfu6i_q {
  d: path("M3 21C3 10.5 10.5 3 21 3c0 5-1 8-2.5 10l-2.5-.5l.5 3l-3 .25v2.75C10 20.5 6.5 21 3 21Zm0 0l5-5");
}

</style>
