<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmfyj3b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:home-office" /></template>
<style>
.lmfyj3b9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5h5m-2.5 0v-9l5-6m2-2l1.193.398a1.5 1.5 0 0 1 .797 2.218l-.24.384a1.424 1.424 0 0 1-2.438-.037l-.719-1.231A1.192 1.192 0 0 1 12 4.5m2 8h5a1.5 1.5 0 0 1 1.5 1.5v2.5A1.5 1.5 0 0 1 19 18h-5a1.5 1.5 0 0 1-1.5-1.5V14a1.5 1.5 0 0 1 1.5-1.5m-.419 5.5h5.838a1.5 1.5 0 0 1 1.423 1.026L21 19.5a1.14 1.14 0 0 1-1.081 1.5h-6.838A1.14 1.14 0 0 1 12 19.5l.158-.474A1.5 1.5 0 0 1 13.581 18");
}

</style>
