<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="n296trb-r"/><circle class="h-qsumbid"/><circle class="g9wm5ub3y"/><circle class="dl_10cc_n"/></g><path class="nrd_dbcjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audi-bkk-epa" /></template>
<style>
.dl_10cc_n {
  cx: 38.433px;
  cy: 25px;
  r: 6.067px;
}

.g9wm5ub3y {
  cx: 28.811px;
  cy: 25px;
  r: 6.067px;
}

.h-qsumbid {
  cx: 19.189px;
  cy: 25px;
  r: 6.067px;
}

.n296trb-r {
  cx: 9.567px;
  cy: 25px;
  r: 6.067px;
}

.nrd_dbcjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.35 9.5a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.3m7.05-4v8m4.3 0l-3.294-4L26.4 5.527M23.106 9.5H22.1m6.55-4v8m4.3 0l-3.294-4l3.294-3.973M29.656 9.5H28.65m-9.862 31.99a2 2 0 0 1-1.738 1.01h0a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v.65h-4m6.38 2.65v-8h2.618c1.48 0 2.681 1.203 2.681 2.687s-1.2 2.686-2.68 2.686h-2.62m11.451-.023h-3.544m-.878 2.65l2.65-8l2.65 8");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
