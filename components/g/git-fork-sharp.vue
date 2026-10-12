<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="f9xu_cb8q"/><circle class="dxajnmbvk"/><circle class="tyhetpb4e"/><path class="fygqrlb-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-fork-sharp" /></template>
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

.fygqrlb-u {
  d: path("M6.5 7.5v4.25h11V7.5M12 11.75v4.5");
}

.tyhetpb4e {
  cx: 12px;
  cy: 18.75px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
