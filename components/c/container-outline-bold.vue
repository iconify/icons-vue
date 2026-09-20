<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xxsav7b5u"/><path class="vavi9cbgb"/><path class="x5li7lwaz"/><path class="bppr_wbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:container-outline-bold" /></template>
<style>
.bppr_wbcq {
  d: path("M16 7v12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vavi9cbgb {
  d: path("M8 7v12");
}

.x5li7lwaz {
  d: path("M12 7v12");
}

.xxsav7b5u {
  d: path("M3 9a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
