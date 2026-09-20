<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q6zj4iekt"/><path class="kburqr_hv"/><path class="pty_wsbvs"/><path class="gcalxb98a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cast-duotone-bold" /></template>
<style>
.gcalxb98a {
  d: path("M8 13h8");
}

.kburqr_hv {
  d: path("M8 4h8v13h4v4H8Z");
}

.pty_wsbvs {
  d: path("M8 9h8");
}

.q6zj4iekt {
  fill: currentColor;
  d: path("M8 4h8v13h4v4H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
