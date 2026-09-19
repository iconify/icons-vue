<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w_548nbrx"/><path class="g-a3y9b2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:forcepoint-vpn" /></template>
<style>
.g-a3y9b2p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 21.944V42.5l12.333-10.278z");
}

.w_548nbrx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.556 5.5h32.889v8.222H15.777V42.5H7.556z");
}

</style>
