<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="huded_cfc"/><path class="j_m2_nbag"/><path class="xao2ebc6f"/><path class="tb3edh0qa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevron-last-duotone-bold" /></template>
<style>
.huded_cfc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j_m2_nbag {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m5 5 7 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tb3edh0qa {
  d: path("m5 5 7 7 -7 7");
}

.xao2ebc6f {
  d: path("M21 5v14");
}

</style>
