<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="lieeyubpt"/><path class="v9xun51an"/></g><path class="gdpz_rbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-fossify-8" /></template>
<style>
.gdpz_rbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.532 9.567h24.936a4 4 0 0 1 4 4V38.5a4 4 0 0 1-4 4H11.532a4 4 0 0 1-4-4V13.567a4 4 0 0 1 4-4M13.715 5.5v4.068M34.14 5.5v4.068M9.731 19.89h28.36");
}

.lieeyubpt {
  d: path("M24.91 31.195h-1.82c-1.54 0-2.8 1.26-2.8 2.8h0c0 1.54 1.26 2.8 2.8 2.8h1.82c1.54 0 2.8-1.26 2.8-2.8h0c0-1.54-1.26-2.8-2.8-2.8");
}

.v9xun51an {
  d: path("M24.91 31.195c1.54 0 2.8-1.26 2.8-2.8h0c0-1.54-1.26-2.8-2.8-2.8h-1.82c-1.54 0-2.8 1.26-2.8 2.8h0c0 1.54 1.26 2.8 2.8 2.8");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
