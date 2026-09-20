<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bna3wq9uo"/><path class="ucbzzjbat"/><path class="t3_tm1wcl"/><path class="mckspnbyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:highlighter-duotone-bold" /></template>
<style>
.bna3wq9uo {
  fill: currentColor;
  d: path("m11 11 3 -3 2 2 -3 3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mckspnbyn {
  d: path("M3 17h9");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t3_tm1wcl {
  d: path("m14 8 4 -4");
}

.ucbzzjbat {
  d: path("m11 11 3 -3 2 2 -3 3Z");
}

</style>
