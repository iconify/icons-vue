<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m1wco1b3l"/><path class="n5rsk3bsy"/><circle class="znaicmrtz"/><circle class="qmoxv5bji"/><circle class="nvm3z7gpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:facer" /></template>
<style>
.m1wco1b3l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.779 12.777h26.054a3.649 3.649 0 1 0 0-7.298H9.48a4 4 0 0 0-4 4V38.83a3.649 3.649 0 1 0 7.298 0z");
}

.n5rsk3bsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.927 23.573h16.481l3.55-7.297h-20.03a3.649 3.649 0 1 0 0 7.298Zm3.648 10.143h8.068l4.035-7.298h-15.4a4 4 0 0 0-4 4V42.48h7.297z");
}

.nvm3z7gpf {
  cx: 19.972px;
  cy: 30.159px;
  r: 0.75px;
  fill: currentColor;
}

.qmoxv5bji {
  cx: 9.63px;
  cy: 9.583px;
  r: 0.75px;
  fill: currentColor;
}

.znaicmrtz {
  cx: 19.972px;
  cy: 19.924px;
  r: 0.75px;
  fill: currentColor;
}

</style>
