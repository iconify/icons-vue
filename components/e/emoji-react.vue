<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="y3nhvudao"/><path class="ktufmabdh"/><path class="v5x_aacpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:emoji-react" /></template>
<style>
.ktufmabdh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 11.75h.01m5.49 0h.01");
}

.v5x_aacpn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 15.5a4 4 0 0 0 6.5 0m5.5-12.75v4m-2-2h4");
}

.y3nhvudao {
  cx: 10.5px;
  cy: 13.5px;
  r: 7.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
