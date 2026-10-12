<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="yx0qaibdx"/><circle class="fdj2t-bow"/><circle class="ejxhftm9h"/><path class="wr2docblg"/><path class="ipchewbfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bouquet-flowers" /></template>
<style>
.ejxhftm9h {
  cx: 12px;
  cy: 5px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.fdj2t-bow {
  cx: 18px;
  cy: 7.5px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipchewbfw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 9.5L9 11.75m7.75-2.25L15 11.75M12 8v3.75m-5.6 0h11.2q.9 0 .5.8l-3.95 7.9q-.4.8-1.3.8h-1.7q-.9 0-1.3-.8l-3.95-7.9q-.4-.8.5-.8m2.1 3.5h7");
}

.wr2docblg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7.5h.01M18 7.5h.01M12 5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yx0qaibdx {
  cx: 6px;
  cy: 7.5px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
