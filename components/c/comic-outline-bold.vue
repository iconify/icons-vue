<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vyks9vbfn"/><path class="r7xk8o29f"/><path class="rzfubwb2e"/><path class="p_6dl25_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:comic-outline-bold" /></template>
<style>
.p_6dl25_i {
  d: path("M5 6h5v5H7.5L5 13.5V11Z");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.rzfubwb2e {
  d: path("M12 12h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vyks9vbfn {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
