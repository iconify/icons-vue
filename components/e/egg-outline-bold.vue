<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q-5l-qhcw"/><path class="v29fxrpgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:egg-outline-bold" /></template>
<style>
.q-5l-qhcw {
  d: path("M12 21c-4 0 -6 -3 -6 -7C6 9 9 4 12 4s6 5 6 10c0 4 -2 7 -6 7");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v29fxrpgx {
  d: path("m8 13 2 2 2 -2 2 2 2 -2");
}

</style>
