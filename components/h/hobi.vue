<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dg712yv-p"/><rect class="o0n67e52f"/><circle class="ub5o7jrrf"/><path class="y9jumnslg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hobi" /></template>
<style>
.dg712yv-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-28 13.506V29.59m7.012-10.584V29.59M10.5 24.278h7.012");
}

.o0n67e52f {
  width: 5.292px;
  height: 7.012px;
  x: 20.333px;
  y: 22.578px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.646px;
  ry: 2.646px;
}

.ub5o7jrrf {
  cx: 36.574px;
  cy: 19.337px;
  r: 0.75px;
  fill: currentColor;
}

.y9jumnslg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.574 22.578v7.012m-8.111-4.366a2.646 2.646 0 1 1 5.292 0v1.72a2.646 2.646 0 1 1-5.292 0m0 2.646V19.006");
}

</style>
