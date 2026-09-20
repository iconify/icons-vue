<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="up9hpnb5j"/><path class="pdovjob2m"/><path class="su0_1cb8y"/><path class="rso90bchv"/><path class="w_j_p0-ts"/><path class="sfn7tmb6c"/><path class="t_-p3gl9a"/><path class="zg6lybc6r"/><path class="h3f_66bxu"/><path class="i3md2ibef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:continuous-batch-duotone-bold" /></template>
<style>
.h3f_66bxu {
  d: path("M14 12h5a3 3 0 0 1 3 3v3a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3v-3l3 -3h5");
}

.i3md2ibef {
  d: path("M5 16.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.pdovjob2m {
  fill: currentColor;
  d: path("M8 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rso90bchv {
  fill: currentColor;
  d: path("M14 12h5a3 3 0 0 1 3 3v3a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3v-3l3 -3h5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sfn7tmb6c {
  d: path("M4 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.su0_1cb8y {
  fill: currentColor;
  d: path("M12 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.t_-p3gl9a {
  d: path("M8 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.up9hpnb5j {
  fill: currentColor;
  d: path("M4 4a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.w_j_p0-ts {
  fill: currentColor;
  d: path("M5 16.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zg6lybc6r {
  d: path("M12 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
