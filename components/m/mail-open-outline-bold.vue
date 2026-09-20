<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ckawxab4i"/><path class="zr5lbkq8n"/><path class="ujkepejes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mail-open-outline-bold" /></template>
<style>
.ckawxab4i {
  d: path("m4 11 8 -8 8 8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ujkepejes {
  d: path("m6 12 6 6 6 -6");
}

.zr5lbkq8n {
  d: path("M4 11v10h16V11");
}

</style>
