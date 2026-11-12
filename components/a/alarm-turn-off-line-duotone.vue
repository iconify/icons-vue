<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="nd-3gubon"/><path class="grjk2ibua"/><path class="x43s2zn6y"/><path class="pfllnjb4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alarm-turn-off-line-duotone" /></template>
<style>
.grjk2ibua {
  d: path("M14.1215 15.1214L12.0002 13M12.0002 13L9.87891 10.8787M12.0002 13L14.1216 10.8787M12.0002 13L9.87892 15.1213");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nd-3gubon {
  cx: 12px;
  cy: 13px;
  r: 9px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.pfllnjb4h {
  stroke-linejoin: round;
  d: path("M20.5 4.5L16.5 2");
}

.x43s2zn6y {
  stroke-linejoin: round;
  d: path("M3.5 4.5L7.50002 2");
}

</style>
