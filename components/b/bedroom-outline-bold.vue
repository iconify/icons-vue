<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="rr18_ccge"/><path class="bod4n0b3z"/><path class="qhxvxhy0o"/><path class="azj37obeu"/><path class="tu0fdo1xi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bedroom-outline-bold" /></template>
<style>
.azj37obeu {
  d: path("M12 2v10");
}

.bod4n0b3z {
  d: path("M2 18h20");
}

.qhxvxhy0o {
  d: path("M7 4a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

.rr18_ccge {
  d: path("M2 21v-6h20v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tu0fdo1xi {
  d: path("M7 7h10");
}

</style>
