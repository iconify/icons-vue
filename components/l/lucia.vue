<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="dkfbp49qd"/><path class="zen52_ror"/><path class="lr32f3pcg"/><path class="w3zrjeb-r"/><path class="ydqthzbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lucia" /></template>
<style>
.dkfbp49qd {
  cx: 29.826px;
  cy: 18.167px;
  r: 0.75px;
  fill: currentColor;
}

.lr32f3pcg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.469 29.038c-.565 0-1.13-.565-1.13-1.13v-6.352m19.971 4.658a2.83 2.83 0 0 1-2.823 2.824h0a2.83 2.83 0 0 1-2.824-2.824V24.38a2.83 2.83 0 0 1 2.824-2.823h0a2.83 2.83 0 0 1 2.823 2.823");
}

.w3zrjeb-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.44 29.038c-.565 0-1.13-.565-1.13-1.13v-6.352");
}

.ydqthzbbt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4");
}

.zen52_ror {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.826 21.584v7.454M8.56 17.744v9.882c0 .847.565 1.411 1.412 1.411h.424m16.594-1.411c-.424.847-1.412 1.412-2.4 1.412h0a2.83 2.83 0 0 1-2.824-2.824v-1.835a2.83 2.83 0 0 1 2.823-2.824h0c.989 0 1.977.565 2.4 1.412m-8.649 3.247a2.83 2.83 0 0 1-2.824 2.824h0a2.83 2.83 0 0 1-2.824-2.824v-4.658");
}

</style>
