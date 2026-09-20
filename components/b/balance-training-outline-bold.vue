<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w08657bnd"/><path class="icy6dnbvy"/><path class="n-7t0yb1r"/><path class="esz0ytbwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:balance-training-outline-bold" /></template>
<style>
.esz0ytbwn {
  d: path("M8 17a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.icy6dnbvy {
  d: path("M12 8v5");
}

.n-7t0yb1r {
  d: path("M3 13h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w08657bnd {
  d: path("M9 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
