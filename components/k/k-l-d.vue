<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="he0znwbih"/><path class="z1906ln_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:k-l-d" /></template>
<style>
.he0znwbih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.879 0 21.5 9.621 21.5 21.5S35.879 45.5 24 45.5S2.5 35.879 2.5 24S12.121 2.5 24 2.5");
}

.z1906ln_o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.037 16.034c-2.336 5.458.194 11.777 5.652 14.114c5.458 2.336 11.776-.194 14.113-5.652q.105-.245.198-.496c2.2-5.515 8.454-8.203 13.97-6.004c5.515 2.2 8.203 8.454 6.004 13.97");
}

</style>
