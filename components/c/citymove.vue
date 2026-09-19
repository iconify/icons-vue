<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="uwumjrbdx"/><circle class="c5jfmhtym"/><path class="hy4dzrb6q"/><circle class="ldozv10rs"/><path class="al__ykb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:citymove" /></template>
<style>
.al__ykb2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.127 30.072c-2.75-7.154-.216-15.267 6.109-19.561a16.33 16.33 0 0 1 20.347 1.596m-.316 24.014c-6.254 5.71-16.038 5.697-22.275-.03");
}

.c5jfmhtym {
  cx: 13.878px;
  cy: 33.15px;
  r: 1.679px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hy4dzrb6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.994 41.917a20.499 20.499 0 1 1-.538-36.122");
}

.ldozv10rs {
  cx: 39.752px;
  cy: 8.407px;
  r: 1.679px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uwumjrbdx {
  cx: 39.785px;
  cy: 39.535px;
  r: 1.679px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
