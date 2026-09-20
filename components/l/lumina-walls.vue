<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="tup6dubcl"/><path class="vm0l07rqz"/></g><g class="y9tr6bcfx"><path class="fc26erbuv"/><path class="f94lhzbhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lumina-walls" /></template>
<style>
.f94lhzbhc {
  d: path("M29.106 21.605a10.24 10.24 0 0 0 10.262-10.262V5.59");
}

.fc26erbuv {
  d: path("M36.916 5.589A10.24 10.24 0 0 0 26.655 15.85v5.754h5.583A10.24 10.24 0 0 0 42.5 11.343V5.59z");
}

.tup6dubcl {
  d: path("M23.89 28.855c.247-3.15 2.528-4.554 5.11-4.554h.824c4.193.013 8.39-.043 12.583 0l-.001 7.848a10.24 10.24 0 0 1-10.262 10.262H15.762A10.24 10.24 0 0 1 5.5 32.15V5.655h8.106A10.24 10.24 0 0 1 23.87 15.917V28.31c0 3.557 2.396 5.13 5.13 5.13h13.01");
}

.vm0l07rqz {
  d: path("M25.06 42.411A10.24 10.24 0 0 1 14.8 32.15V18.617c0-2.132-1.692-3.848-3.823-3.848H5.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
