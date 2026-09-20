<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zwghjjvbs"/><path class="azskw1rof"/><path class="fbyngunlt"/><path class="bie4u9bix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:greedy-outline-bold" /></template>
<style>
.azskw1rof {
  d: path("m9 16 5 -5");
}

.bie4u9bix {
  d: path("M19 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.fbyngunlt {
  d: path("M14 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zwghjjvbs {
  d: path("M2 16h7");
}

</style>
