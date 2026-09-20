<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bod4n0b3z"/><path class="rbmqb921v"/><path class="nhpfz0btj"/><path class="dgfbh6b4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:frost-outline-bold" /></template>
<style>
.bod4n0b3z {
  d: path("M2 18h20");
}

.dgfbh6b4z {
  d: path("M12 9v9");
}

.nhpfz0btj {
  d: path("M17 7.5v7m-3.5 0 7 -7");
}

.rbmqb921v {
  d: path("M7 7.5v7m-3.5 0 7 -7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
