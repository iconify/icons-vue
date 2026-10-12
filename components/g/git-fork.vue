<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="f9xu_cb8q"/><circle class="dxajnmbvk"/><circle class="tyhetpb4e"/><path class="h4z-n8bhd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-fork" /></template>
<style>
.dxajnmbvk {
  cx: 17.5px;
  cy: 5.25px;
  r: 2.25px;
}

.f9xu_cb8q {
  cx: 6.5px;
  cy: 5.25px;
  r: 2.25px;
}

.h4z-n8bhd {
  d: path("M6.5 7.5v1.75a2.5 2.5 0 0 0 2.5 2.5h6a2.5 2.5 0 0 0 2.5-2.5V7.5M12 11.75v4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tyhetpb4e {
  cx: 12px;
  cy: 18.75px;
  r: 2.25px;
}

</style>
