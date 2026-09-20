<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="n2ax9c9wi"/><path class="nge7ozc5q"/></g><path class="gdpz_rbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-fossify-28" /></template>
<style>
.gdpz_rbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.532 9.567h24.936a4 4 0 0 1 4 4V38.5a4 4 0 0 1-4 4H11.532a4 4 0 0 1-4-4V13.567a4 4 0 0 1 4-4M13.715 5.5v4.068M34.14 5.5v4.068M9.731 19.89h28.36");
}

.n2ax9c9wi {
  d: path("M15.389 29.329c0-2.074 1.659-3.734 3.595-3.734s3.733 1.66 3.733 3.734c0 .968-.415 1.935-1.106 2.627c-1.521 1.244-6.222 4.84-6.222 4.84h7.328m7.261-5.601h-1.82c-1.54 0-2.8 1.26-2.8 2.8s1.26 2.8 2.8 2.8h1.82c1.54 0 2.8-1.26 2.8-2.8s-1.26-2.8-2.8-2.8");
}

.nge7ozc5q {
  d: path("M29.978 31.195c1.54 0 2.8-1.26 2.8-2.8s-1.26-2.8-2.8-2.8h-1.82c-1.54 0-2.8 1.26-2.8 2.8s1.26 2.8 2.8 2.8");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
