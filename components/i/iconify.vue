<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="to-5kdesz"><path class="pyx85bckz"/><circle class="g1rba9-mw"/><path class="z0oqahuzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iconify" /></template>
<style>
.g1rba9-mw {
  cx: 24px;
  cy: 18.023px;
  r: 3.852px;
  stroke-linecap: round;
}

.pyx85bckz {
  stroke-linecap: round;
  d: path("M24 3.5c-2.501 0-13.5 10.942-15.878 18.888h.035a16.8 16.8 0 0 0-.915 5.357C7.242 36.998 14.745 44.5 24 44.5s16.758-7.502 16.758-16.755a16.7 16.7 0 0 0-.882-5.357h.004C37.502 14.442 26.5 3.5 24 3.5");
}

.to-5kdesz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.z0oqahuzs {
  d: path("M18.403 23.785c2.297.096 3.044 3.357 5.598 3.788s3.834-.772 3.834-.772A5.7 5.7 0 0 1 24 36.719c-3.148 0-5.7-2.552-5.7-5.676z");
}

</style>
