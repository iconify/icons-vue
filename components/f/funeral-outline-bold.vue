<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="a5yfw13jk"/><path class="zka_zabrc"/><path class="kdybz_aht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:funeral-outline-bold" /></template>
<style>
.a5yfw13jk {
  d: path("M6 21V10c0 -5 12 -5 12 0v11Z");
}

.kdybz_aht {
  d: path("M9 17h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zka_zabrc {
  d: path("M9 13h6");
}

</style>
