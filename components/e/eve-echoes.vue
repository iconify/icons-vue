<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mgry2ct_q"/><rect class="ey5pd3b-a"/><path class="cd7bep4rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eve-echoes" /></template>
<style>
.cd7bep4rd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.333 15.215H4.5v1.083m0 2.979h10.833M4.5 22.256v1.084h10.833m3.521-8.125L24 24.423l5.146-9.208m14.354-.056H32.667v1.083m0 3.035H43.5M32.667 22.2v1.083H43.5");
}

.ey5pd3b-a {
  width: 2.518px;
  height: 3.8px;
  x: 25.731px;
  y: 28.987px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.259px;
  ry: 1.259px;
}

.mgry2ct_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.443 28.994v3.8m2.517-3.8v3.8m-2.517-1.907h2.517m16.423 1.484c.233.303.525.416.932.416h.562a.95.95 0 0 0 .948-.95a.95.95 0 0 0-.948-.95h-.62a.95.95 0 1 1 .002-1.9h.56c.406 0 .698.113.931.417M15.672 31.52v.016a1.259 1.259 0 0 1-2.518 0v-1.283a1.259 1.259 0 1 1 2.518 0v.016m-8.497.625H8.41m.665 1.9h-1.9v-3.8h1.9m23.253 1.893h1.235m.665 1.9h-1.9v-3.8h1.9");
}

</style>
