<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fuu4qgbtd"/><path class="hwyorhbry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camping-tent-sharp" /></template>
<style>
.fuu4qgbtd {
  d: path("M2.75 21.25c0-8.25 4.25-15 9.25-15s9.25 6.75 9.25 15Z");
}

.hwyorhbry {
  d: path("M12 9.75c-1.5 3-2.25 6.25-2.25 11.5h4.5c0-5.25-.75-8.5-2.25-11.5Zm0-3.5V3.5l2 .75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
