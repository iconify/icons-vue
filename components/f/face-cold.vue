<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="c9s6xi_fd"/><path class="pkxclebiu"/><path class="txc_unbkh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-cold" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.c9s6xi_fd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.15 6.5h.7q.4 0 .29.39l-.53 1.97q-.11.39-.22 0l-.53-1.97q-.11-.39.29-.39m3.5-.5h.7q.4 0 .3.39l-.55 2.22q-.1.39-.2 0l-.55-2.22q-.1-.39.3-.39m3.5.5h.7q.4 0 .29.39l-.53 1.97q-.11.39-.22 0l-.53-1.97q-.11-.39.29-.39");
}

.pkxclebiu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 11.5h.01m5.99 0h.01");
}

.txc_unbkh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 16.75l1.33-1l1.33 1l1.33-1l1.33 1l1.33-1l1.33 1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
