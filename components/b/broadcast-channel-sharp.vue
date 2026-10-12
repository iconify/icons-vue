<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ifob98x5h"/><path class="sgb83qbng"/><path class="j6hkyqfqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:broadcast-channel-sharp" /></template>
<style>
.ifob98x5h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.25v-2.5h18.5v14H12.5L8 20.85l-1.25 1v-4.1h-4v-2.5Z");
}

.j6hkyqfqp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 8.25l-2.552 2.5l2.552 2.5m5-5l2.552 2.5l-2.552 2.5");
}

.sgb83qbng {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
