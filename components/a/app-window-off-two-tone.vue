<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fz4bgpf4d"/><path class="w_pnn5b3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:app-window-off-two-tone" /></template>
<style>
.fz4bgpf4d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.8284 20.8284C20.1046 21.5523 19.1046 22 18 22H6C3.7909 22 2 20.2091 2 18V6C2 4.8955 2.4477 3.8955 3.1716 3.1716L20.8284 20.8284ZM20.2929 16.0502L7.9498 3.7071C7.7688 3.5261 7.6569 3.2761 7.6569 3C7.6569 2.4477 8.1046 2 8.6569 2H18C20.2091 2 22 3.7909 22 6V15.3431C22 15.8954 21.5523 16.3431 21 16.3431C20.7239 16.3431 20.4739 16.2312 20.2929 16.0502Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w_pnn5b3g {
  d: path("M20.1213 20.1213C19.5785 20.6642 18.8285 21 18 21H6C4.3431 21 3 19.6569 3 18V6C3 5.1715 3.3358 4.4215 3.8787 3.8787M2 2L22 22");
}

</style>
