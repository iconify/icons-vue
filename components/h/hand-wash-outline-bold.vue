<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="znimqt98n"/><path class="mqbr2yyal"/><path class="ehnvkinxp"/><path class="i2-ny_bzf"/><path class="rsinobb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hand-wash-outline-bold" /></template>
<style>
.ehnvkinxp {
  d: path("M7 4v4");
}

.i2-ny_bzf {
  d: path("M12 3v4");
}

.mqbr2yyal {
  d: path("M19 21v-6a2 2 0 0 0 -4 0");
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

.znimqt98n {
  d: path("M5 21v-6a2 2 0 0 1 4 0v-3a2 2 0 0 1 4 0v4");
}

</style>
