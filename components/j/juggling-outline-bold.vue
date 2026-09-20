<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hrm50umfz"/><path class="d_xtg74gy"/><path class="mor-ojbak"/><path class="gcpl_duni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:juggling-outline-bold" /></template>
<style>
.d_xtg74gy {
  d: path("M15 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.gcpl_duni {
  d: path("M12 4c6 1 8 7 4 11");
}

.hrm50umfz {
  d: path("M6 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.mor-ojbak {
  d: path("M7 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
