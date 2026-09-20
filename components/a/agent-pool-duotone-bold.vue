<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kfivtob2o"/><path class="yo09w9bsd"/><path class="pk7qwlbxv"/><path class="xyeuuzvcq"/><path class="gsa3wh0sx"/><path class="quu8uycwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-pool-duotone-bold" /></template>
<style>
.gsa3wh0sx {
  d: path("M17.77 4.78a3 3 0 1 1 -2.54 0");
}

.kfivtob2o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.77 4.78a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pk7qwlbxv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 14v5h18v-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.quu8uycwi {
  d: path("M3 14v5h18v-5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xyeuuzvcq {
  d: path("M8.77 4.78a3 3 0 1 1 -2.54 0");
}

.yo09w9bsd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17.77 4.78a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
