<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="bfu1rrb0k"/><circle class="sruv5_b8f"/><circle class="u0gutabcx"/><circle class="e12nyyb1t"/><circle class="dbjv16wxy"/><circle class="raagn-npo"/><circle class="ro00ggbqz"/><path class="qaec5ebju"/></g><g class="y9tr6bcfx"><path class="iv3_27bem"/><circle class="xeulypbau"/><circle class="jxry1sbmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arcticons-happy" /></template>
<style>
.bfu1rrb0k {
  d: path("m24 10.84l-11.4 6.58v13.16L24 37.16l11.4-6.58V17.42z");
}

.dbjv16wxy {
  cx: 39.93px;
  cy: 33.2px;
  r: 3.11px;
}

.e12nyyb1t {
  cx: 39.93px;
  cy: 14.8px;
  r: 3.11px;
}

.iv3_27bem {
  d: path("M28.993 27.3c-1.488 1.156-3.054 1.67-4.993 1.67c-1.938 0-3.505-.514-4.993-1.67");
}

.jxry1sbmr {
  cx: 28.516px;
  cy: 21.621px;
  r: 2.592px;
}

.qaec5ebju {
  d: path("m12.6 30.58l-1.84 1.06M24 37.16v2.12m0-28.44V8.71m11.4 21.87l1.84 1.06M35.4 17.42l1.84-1.06M12.6 17.42l-1.84-1.06");
}

.raagn-npo {
  cx: 24px;
  cy: 42.39px;
  r: 3.11px;
}

.ro00ggbqz {
  cx: 8.07px;
  cy: 33.2px;
  r: 3.11px;
}

.sruv5_b8f {
  cx: 8.07px;
  cy: 14.8px;
  r: 3.11px;
}

.u0gutabcx {
  cx: 24px;
  cy: 5.61px;
  r: 3.11px;
}

.xeulypbau {
  cx: 19.484px;
  cy: 21.621px;
  r: 2.592px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
