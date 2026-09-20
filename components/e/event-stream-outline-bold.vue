<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ucd8o6bjf"/><path class="nbncjhbtk"/><path class="qp5e0_b3n"/><path class="tdk6nzbaw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-stream-outline-bold" /></template>
<style>
.nbncjhbtk {
  d: path("M7.5 7.5 10 10");
}

.qp5e0_b3n {
  d: path("M12.5 12.5 15 15");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tdk6nzbaw {
  d: path("M20.5 17v3.5H17");
}

.ucd8o6bjf {
  d: path("M2.5 2.5 5 5");
}

</style>
