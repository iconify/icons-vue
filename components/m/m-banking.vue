<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w6jpzpl3w"/><path class="zvn998bvh"/><path class="utagtgbcx"/><path class="iphotbbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:m-banking" /></template>
<style>
.iphotbbqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.366 33.741h6.345L44.5 24l-9.789-9.741l-12.93 12.929");
}

.utagtgbcx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.366 33.741l10.019-9.989l-3.494-3.494l-10.02 10.019");
}

.w6jpzpl3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.828 14.259L11.039 24l9.789 9.741");
}

.zvn998bvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.366 33.741L18.578 24l9.788-9.741H13.289L3.5 24l9.789 9.741z");
}

</style>
