<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lwk28k3zq"/><path class="skbifdbcx"/><path class="dfl4nkbui"/><path class="m8uexfcos"/><path class="lc5qczbkz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-report-duotone-bold" /></template>
<style>
.dfl4nkbui {
  d: path("M12 16a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.lc5qczbkz {
  d: path("M16.5 16H21");
}

.lwk28k3zq {
  fill: currentColor;
  d: path("M12 16a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.m8uexfcos {
  d: path("M16.5 11.5V16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.skbifdbcx {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>
