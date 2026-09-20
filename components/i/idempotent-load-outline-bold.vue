<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="buvqhc29l"/><path class="hl79yp-tj"/><path class="dhcdkb-uh"/><path class="j12otbcul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:idempotent-load-outline-bold" /></template>
<style>
.buvqhc29l {
  d: path("M2 15a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.dhcdkb-uh {
  d: path("m18 9 -3 -3");
}

.hl79yp-tj {
  d: path("M6 4h12v5");
}

.j12otbcul {
  d: path("m8 17 3 3 5 -5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
