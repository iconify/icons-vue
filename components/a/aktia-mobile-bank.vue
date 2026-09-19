<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vsgtvnb8h"/><ellipse class="h3_ybuybd"/><path class="ppcyvacdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aktia-mobile-bank" /></template>
<style>
.h3_ybuybd {
  cx: 31.228px;
  cy: 19.371px;
  fill: currentColor;
  rx: 0.765px;
  ry: 0.75px;
}

.ppcyvacdx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.228 22.591v7.112M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.vsgtvnb8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.412 29.703l-3.391-10.976L9.5 29.703m1.174-3.705h4.565m3.127-7.074v10.779m0-2.291l5.178-4.85m-3.596 3.368l4.171 3.773m3.097-10.375v8.893c0 .889.679 1.482 1.698 1.482h.51m-3.907-7.855h3.567m8.552 5.744c0 1.16-.973 2.11-2.161 2.11s-2.16-.95-2.16-2.11V26.22c0-1.161.971-2.111 2.16-2.111s2.16.95 2.16 2.11m.865 3.484c-.432 0-.864-.422-.864-.845v-4.75");
}

</style>
