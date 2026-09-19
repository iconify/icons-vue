<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ovm6amvoq"/><path class="v4t6bnbbh"/><path class="iwxnibdoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:journey" /></template>
<style>
.iwxnibdoz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.519 10.047V7.515A2.02 2.02 0 0 1 13.534 5.5h20.932a2.02 2.02 0 0 1 2.015 2.015v2.532");
}

.ovm6amvoq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.139 42.5H7.86a2.07 2.07 0 0 1-2.069-2.07V17.78a2.07 2.07 0 0 1 2.07-2.069h32.277a2.07 2.07 0 0 1 2.069 2.07v22.65a2.07 2.07 0 0 1-2.07 2.069");
}

.v4t6bnbbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.502 29.411v-7.886h8.285m6.212 15.129h8.324V28.7M8.462 15.713v-3.651a2.02 2.02 0 0 1 2.015-2.015h27.046a2.02 2.02 0 0 1 2.015 2.015v3.65");
}

</style>
