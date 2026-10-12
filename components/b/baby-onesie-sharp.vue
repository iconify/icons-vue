<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="wvq192bfw"/><path class="pwfcu_bse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-onesie-sharp" /></template>
<style>
.pwfcu_bse {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 18h.01m2.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wvq192bfw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.49 3.76l1.77 1.23l.74.51l.74-.51l1.77-1.23l.74-.51l.8.4l2.9 1.45l.8.4l.3.85l.9 2.55l.3.85l-.83.35l-1.34.55l-.83.35l-.64-.64l-.22-.22l-.64-.64V17l-.53.73l-1.69 2.29l-.53.73h-4l-.53-.73l-1.69-2.29l-.53-.73V9.5l-.64.64l-.22.22l-.64.64l-.83-.35l-1.34-.55l-.83-.35l.3-.85l.9-2.55l.3-.85l.8-.4l2.9-1.45l.8-.4z");
}

</style>
