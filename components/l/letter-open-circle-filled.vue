<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGAyZeFeSE"><path class="k5-vjlrin"/><path class="plg8vpbwb"/><path class="bv3-sab6g"/><path class="fb5pv9qfv"/><path clip-rule="evenodd" class="kmgvyze9z"/><path clip-rule="evenodd" class="jjiubfb0p"/><path clip-rule="evenodd" class="e-yp-mb0b"/></mask></defs><circle mask="url(#SVGAyZeFeSE)" class="bd9gczbnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:letter-open-circle-filled" /></template>
<style>
.bd9gczbnq {
  cx: 13px;
  cy: 13px;
  r: 13px;
  fill: currentColor;
}

.bv3-sab6g {
  stroke: var(--svg-color--000, #000);
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m13 17.5l-6.5-4.33V8.5h13v4.67zm-4.5-9l4.5-3l4.5 3");
}

.e-yp-mb0b {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M12.445 4.668a1 1 0 0 1 1.11 0l4.5 3l-1.11 1.664L13 6.702l-3.945 2.63l-1.11-1.664zM9.5 11a.5.5 0 0 1 .5-.5h6a.5.5 0 0 1 0 1h-6a.5.5 0 0 1-.5-.5m.5 2a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5");
}

.fb5pv9qfv {
  stroke: var(--svg-color--000, #000);
  stroke-linecap: round;
  d: path("M10 11h6m-5.5 2h5");
}

.ft5dv1b6b {
  fill: none;
}

.jjiubfb0p {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M5.5 8.5a1 1 0 0 1 1-1h13a1 1 0 0 1 1 1v4.67a1 1 0 0 1-.446.832l-6.5 4.33a1 1 0 0 1-1.108 0l-6.5-4.33a1 1 0 0 1-.446-.832zm2 1v3.135l5.5 3.663l5.5-3.663V9.5z");
}

.k5-vjlrin {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h26v26H0z");
}

.kmgvyze9z {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M5.5 10.5a1 1 0 0 1 1 1v8h13v-8a1 1 0 1 1 2 0v9a1 1 0 0 1-1 1h-15a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1");
}

.plg8vpbwb {
  stroke: var(--svg-color--000, #000);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.5 11.5v9h-15v-9");
}

</style>
