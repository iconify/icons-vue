<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGVbXdqcoY" class="go0ri_bma"/></defs><path class="zqg-uobqg"/><path class="d6jqgybkg"/><path class="nsmf-nlgq"/><use href="#SVGVbXdqcoY" class="c-zrgpb5l"/><use href="#SVGVbXdqcoY" class="c-zrgpb5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:home-network" /></template>
<style>
.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d6jqgybkg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.535 34.326L24 37.791l3.465-3.465");
}

.go0ri_bma {
  fill: none;
  stroke: currentColor;
  d: path("M27.465 34.326L24 37.79l-3.465-3.465c.88-.881 2.102-1.433 3.465-1.433s2.584.552 3.465 1.433");
}

.nsmf-nlgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 32.893a4.88 4.88 0 0 1 3.465 1.433L24 37.79l-3.465-3.465A4.88 4.88 0 0 1 24 32.893m-8.552-3.653c2.197-2.186 5.216-3.537 8.552-3.537s6.355 1.351 8.552 3.536m-22.449-5.345c3.56-3.559 8.47-5.756 13.897-5.756s10.337 2.197 13.897 5.756");
}

.zqg-uobqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 32.893a4.88 4.88 0 0 1 3.465 1.433L24 37.79l-3.465-3.465A4.88 4.88 0 0 1 24 32.893m-8.552-3.653c2.197-2.186 5.216-3.537 8.552-3.537s6.355 1.351 8.552 3.536M4.5 18.291c4.98-4.992 11.888-8.082 19.5-8.082s14.52 3.09 19.5 8.082");
}

</style>
