<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fm3gyyrqp"/><path class="to8m3ibcr"/><path class="wyegadcbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:church" /></template>
<style>
.fm3gyyrqp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20.5v-6.75q0-.75.63-1.16l3.74-2.43Q9 9.75 9 9.25t.58-.98l1.84-1.54q.58-.48 1.16 0l1.84 1.54q.58.48.58.98t.63.91l3.74 2.43q.63.41.63 1.16v6.75q0 .75-.75.75H4.75q-.75 0-.75-.75m8-14.25v-3.5m-1.5 1.5h3");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.wyegadcbh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 21.25v-3a1.75 1.75 0 0 1 3.5 0v3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
