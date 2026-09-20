<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ytqok-bxz"/><path class="gorvssbqo"/><path class="e6cqo_biq"/><path class="kliut9bht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:greedy-decode-outline-bold" /></template>
<style>
.e6cqo_biq {
  d: path("m6 12 5 -5");
}

.gorvssbqo {
  d: path("M17.5 9.5 20 12l-2.5 2.5");
}

.kliut9bht {
  d: path("m10 12 5 5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ytqok-bxz {
  d: path("M2 12h15.5");
}

</style>
