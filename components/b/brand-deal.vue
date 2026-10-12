<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j6s72ccac"/><rect class="wga_vyb7b"/><path class="pqzlzvbxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brand-deal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6s72ccac {
  d: path("M8.75 7.25v-1.5a2 2 0 0 1 2-2h2.5a2 2 0 0 1 2 2v1.5");
}

.pqzlzvbxv {
  d: path("m12.14 11.07l.69 1.53q.14.32.49.35l1.66.18q.35.04.09.27l-1.24 1.13q-.26.23-.19.57l.35 1.64q.07.34-.24.17l-1.45-.84q-.3-.17-.6 0l-1.45.84q-.31.17-.24-.17l.35-1.64q.07-.34-.19-.57L8.93 13.4q-.26-.23.09-.27l1.66-.18q.35-.03.49-.35l.69-1.53q.14-.32.28 0");
}

.wga_vyb7b {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 7.25px;
  rx: 3px;
}

</style>
