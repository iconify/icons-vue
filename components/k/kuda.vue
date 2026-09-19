<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p0mnqcctt"/><path class="v7j9530vw"/><path class="shx0p9b5c"/><path class="iq_6dobra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kuda" /></template>
<style>
.iq_6dobra {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.988 34.882L15.001 24l2.987-10.809M32.824 30.53A2.177 2.177 0 1 0 35 32.705h0a2.177 2.177 0 0 0-2.176-2.177");
}

.p0mnqcctt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4M13 13.118v21.764M19.002 24H13");
}

.shx0p9b5c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.975 34.882L17.001 24l5.974-10.809");
}

.v7j9530vw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.963 34.882L19.002 24l8.961-10.809");
}

</style>
