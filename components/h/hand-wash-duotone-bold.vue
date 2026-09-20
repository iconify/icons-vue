<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="syn4p7brw"/><path class="wy5f5_n8l"/><path class="pd43yny7a"/><path class="jl3jsq9eu"/><path class="qntpmnbel"/><path class="znimqt98n"/><path class="mqbr2yyal"/><path class="ehnvkinxp"/><path class="i2-ny_bzf"/><path class="rsinobb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hand-wash-duotone-bold" /></template>
<style>
.ehnvkinxp {
  d: path("M7 4v4");
}

.i2-ny_bzf {
  d: path("M12 3v4");
}

.jl3jsq9eu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mqbr2yyal {
  d: path("M19 21v-6a2 2 0 0 0 -4 0");
}

.pd43yny7a {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qntpmnbel {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rsinobb0c {
  d: path("M17 4v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.syn4p7brw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 21v-6a2 2 0 0 1 4 0v-3a2 2 0 0 1 4 0v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wy5f5_n8l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 21v-6a2 2 0 0 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.znimqt98n {
  d: path("M5 21v-6a2 2 0 0 1 4 0v-3a2 2 0 0 1 4 0v4");
}

</style>
