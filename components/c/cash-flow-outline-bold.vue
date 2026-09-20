<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ky4omnbla"/><path class="jlpxneb5g"/><path class="caiwqabfd"/><path class="pqrd0wbvk"/><path class="qnpnbmb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cash-flow-outline-bold" /></template>
<style>
.caiwqabfd {
  d: path("M6.5 10.5 9 8l2.5 2.5");
}

.jlpxneb5g {
  d: path("M9 8v8");
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.pqrd0wbvk {
  d: path("M15 8v8");
}

.qnpnbmb3w {
  d: path("M12.5 13.5 15 16l2.5 -2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
