<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fqjp6kb1p"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fluxer" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fqjp6kb1p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 14.515a6.283 6.283 0 0 1-6.283 6.282c-3.857 0-5.026-2.028-6.217-3.141s-2.36-3.141-6.217-3.141a6.283 6.283 0 0 0-6.283 6.282m25 6.406a6.283 6.283 0 0 1-6.283 6.283c-3.857 0-5.026-2.029-6.217-3.142s-2.36-3.141-6.217-3.141a6.283 6.283 0 0 0-6.283 6.283");
}

</style>
