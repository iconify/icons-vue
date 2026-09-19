<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><path class="g-6-ln_0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ebtedge" /></template>
<style>
.f_v_dfbgn {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

.g-6-ln_0u {
  d: path("M24.334 24h6.831m3.647 10.561H24.334V13.439h10.478M21.027 31.896a5.23 5.23 0 0 1-4.552 2.665h0c-2.894 0-5.24-2.364-5.24-5.28v-3.433c0-2.916 2.346-5.28 5.24-5.28h0c2.893 0 5.239 2.364 5.239 5.28v1.716H11.235");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
