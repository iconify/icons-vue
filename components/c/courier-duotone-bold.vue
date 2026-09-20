<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="le41ikb_c"/><path class="ck-genbzu"/><path class="pemn838wn"/><path class="ia4sldbfw"/><path class="g_49w5zuo"/><path class="ts5ij9bsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:courier-duotone-bold" /></template>
<style>
.ck-genbzu {
  fill: currentColor;
  d: path("M8 13v6h8v-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.g_49w5zuo {
  d: path("M8 13v6h8v-6Z");
}

.ia4sldbfw {
  d: path("M3 21a9 9 0 0 1 18 0");
}

.le41ikb_c {
  fill: currentColor;
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.pemn838wn {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ts5ij9bsc {
  d: path("M12 13v6");
}

</style>
