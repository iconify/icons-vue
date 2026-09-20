<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p7369lx9o"/><circle class="b6yjgkcjy"/><circle class="bs6ky-wsz"/><circle class="iqxpcvc8t"/><path class="op-droiiq"/><path class="z1-e6nf4w"/><path class="w98i96b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:docomo-bikeshare" /></template>
<style>
.b6yjgkcjy {
  cx: 24px;
  cy: 24px;
  r: 17.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.bs6ky-wsz {
  cx: 14.25px;
  cy: 27px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iqxpcvc8t {
  cx: 33.25px;
  cy: 27px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.op-droiiq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.125 14.25h2L33.25 27m-10.812-9.375h-3L24.21 29.5m-.999 0h2");
}

.p7369lx9o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.767 18.435A21.5 21.5 0 0 1 24 45.5l2.986-1.724M8.797 8.797A21.5 21.5 0 0 1 42.62 13.25l-2.986-1.724M18.435 44.767A21.5 21.5 0 0 1 5.38 13.249v3.449");
}

.w98i96b0r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.482 17.625h5.408v3.456h-4.019");
}

.z1-e6nf4w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.884 18.625c0 2.541-3.025 8.375-8.678 8.375H14.25l6.388-6.388m-10.48 4.515l3.031.812l3-3m2.881-2.88l-1.92 1.92m2.86 1.093l1.05 2.613");
}

</style>
