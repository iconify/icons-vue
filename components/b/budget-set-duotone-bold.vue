<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e10hmz-ui"/><path class="nreq_9ofo"/><path class="csyuhrrop"/><path class="mvkhxckkt"/><path class="jlfjgzbqx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:budget-set-duotone-bold" /></template>
<style>
.csyuhrrop {
  d: path("M5 14V3h14v11");
}

.e10hmz-ui {
  fill: currentColor;
  d: path("M2 11v10h20V11L12 21Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jlfjgzbqx {
  d: path("M9 9h6");
}

.mvkhxckkt {
  d: path("M12 6v6");
}

.nreq_9ofo {
  d: path("M2 11v10h20V11L12 21Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
