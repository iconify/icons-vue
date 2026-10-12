<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="w6_ucng2d"/><path class="e7o-fvb1a"/><circle class="l-zqvscmh"/><circle class="um74zsb4n"/><path class="kqwjgevpd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:group-chat-social-sharp" /></template>
<style>
.e7o-fvb1a {
  d: path("M2.75 9.5V7h14v11h-7.5L6.5 20.5l-1.25 1V18h-2.5v-2.5Z");
}

.kqwjgevpd {
  d: path("M5.5 15v-2h4v2m.5 0v-2h4v2");
}

.l-zqvscmh {
  cx: 7.5px;
  cy: 11px;
  r: 1.25px;
}

.um74zsb4n {
  cx: 12px;
  cy: 11px;
  r: 1.25px;
}

.w6_ucng2d {
  d: path("M7.25 4.75v-2h14V13h-2v2.5l-2-2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
