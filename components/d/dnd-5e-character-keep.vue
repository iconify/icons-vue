<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="un85kqbur"/><path class="wgn3k1v4x"/><path class="dd_pq48-f"/><path class="ztq0lwb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dnd-5e-character-keep" /></template>
<style>
.dd_pq48-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 37.414L11.688 15.547h24.624zm0 0V45.5M11.688 15.547l-6.34-2.297m30.964 2.297l6.34-2.297");
}

.un85kqbur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5L5.348 13.25v21.5L24 45.5l18.652-10.75v-21.5z");
}

.wgn3k1v4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5L11.688 15.547L5.348 34.75L24 37.414l18.652-2.664l-6.34-19.203z");
}

.ztq0lwb8r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.643 23.724c0 .827.643 1.47 1.47 1.47s1.47-.643 1.47-1.47v-1.47c0-.827-.643-1.47-1.47-1.47c-.735 0-1.47.643-1.47 1.47zm-4.226-1.47c0-.827.643-1.47 1.47-1.47s1.47.643 1.47 1.47c0 .368-.184.735-.46 1.011c-.643.46-2.48 1.93-2.48 1.93h2.94");
}

</style>
