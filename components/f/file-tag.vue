<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="bxsijvklq"/><path class="s0e633ezd"/><path class="g1kxs5bwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-tag" /></template>
<style>
.bxsijvklq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 21.25h-4.5a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5h6.5l5.5 5.5v3.5");
}

.g1kxs5bwq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 16.25h.01");
}

.s0e633ezd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-11 4h4m2.75 2h1.75q.75 0 1.28.53l2.44 2.44q.53.53 0 1.06l-2.19 2.19q-.53.53-1.06 0l-2.44-2.44q-.53-.53-.53-1.28V15q0-.75.75-.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
