<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t9gnp4b0n"/><path class="ae-e09b3w"/><path class="ohhz_s35v"/><path class="yb0sj-xar"/><path class="irg5kslxg"/><path class="styxdpaok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:claim-outline-bold" /></template>
<style>
.ae-e09b3w {
  d: path("M3 12h18");
}

.irg5kslxg {
  d: path("M12 4v3");
}

.ohhz_s35v {
  d: path("M12 12v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.styxdpaok {
  d: path("M11 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.t9gnp4b0n {
  d: path("M3 12a9 9 0 0 1 18 0");
}

.yb0sj-xar {
  d: path("M12 18a2 2 0 0 1 -4 0");
}

</style>
