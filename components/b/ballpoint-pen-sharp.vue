<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="l9qndnc2p"/><path class="egx4f9n0f"/><path class="rwf0j26dh"/><path class="zhq--2b9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ballpoint-pen-sharp" /></template>
<style>
.egx4f9n0f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.07 16.51l1.42 1.42l1.06 1.06l1.06-1.06l7.6-7.61l1.06-1.06l-1.06-1.06l-1.41-1.41l-1.06-1.06l-1.06 1.06l-7.61 7.6l-1.06 1.06zm1.42-3.53l3.53 3.53m4.42-7.95l-3.35 3.35");
}

.l9qndnc2p {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.15 7.14l.71.71l.53.53l.53-.53l.88-.89l.53-.53l-.53-.53l-.7-.7l-.53-.53l-.53.53l-.89.88l-.53.53z");
}

.rwf0j26dh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.41 19.84l2.97-1.35l.46-.21l-.35-.35l-1.42-1.42l-.35-.35l-.21.46l-1.35 2.97l-.21.46z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zhq--2b9z {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.95 20.05h.01");
}

</style>
