<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="aiaavobpr"/><path class="t92aii9xn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:faucet-off" /></template>
<style>
.aiaavobpr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.75h10.5a4.5 4.5 0 0 1 4.5 4.5V15h-4v-1.75a.75.75 0 0 0-.75-.75H2.75Zm5.25 0v-3.5m-2.5 0h5");
}

.t92aii9xn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 19.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
