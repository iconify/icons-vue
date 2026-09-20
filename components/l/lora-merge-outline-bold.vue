<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w122ipbuy"/><path class="udqwuzb_t"/><path class="hdlchkb0j"/><path class="dfxjcnksd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lora-merge-outline-bold" /></template>
<style>
.dfxjcnksd {
  d: path("m16 10 -2 2 2 2");
}

.hdlchkb0j {
  d: path("M14.5 12H17");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.udqwuzb_t {
  d: path("M17.5 10.5a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

.w122ipbuy {
  d: path("M3 6a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
