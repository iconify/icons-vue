<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="waanjrsfn"/><circle class="y16ksbccy"/><circle class="j7op7vb4f"/><circle class="i1yhspbem"/><circle class="gpcr8ac1y"/><circle class="sb2m6db8r"/><path class="kxq38n9-i"/><path class="ll0g54h-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kijiji" /></template>
<style>
.gpcr8ac1y {
  cx: 32.818px;
  cy: 17.933px;
  r: 0.75px;
  fill: currentColor;
}

.i1yhspbem {
  cx: 27.65px;
  cy: 17.933px;
  r: 0.75px;
  fill: currentColor;
}

.j7op7vb4f {
  cx: 22.482px;
  cy: 17.933px;
  r: 0.75px;
  fill: currentColor;
}

.kxq38n9-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.314 20.09v6.497M27.65 20.09v6.497m5.168-6.497v8.172a2.44 2.44 0 0 1-2.429 2.452h0m7.597-10.624v6.497m-28.722-9.71v9.807m.001-2.084l4.439-4.417m-3.026 3.012l3.49 3.474");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.sb2m6db8r {
  cx: 37.986px;
  cy: 17.933px;
  r: 0.75px;
  fill: currentColor;
}

.waanjrsfn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.482 20.09v8.581a2.44 2.44 0 0 1-2.429 2.452h0");
}

.y16ksbccy {
  cx: 17.314px;
  cy: 17.933px;
  r: 0.75px;
  fill: currentColor;
}

</style>
