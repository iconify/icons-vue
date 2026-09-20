<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz139kksf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:climate-mini-split-sharp" /></template>
<style>
.mz139kksf {
  fill: currentColor;
  d: path("M2 12V2h20v10h-4V6H6v6zm5 2h2q0 2.075-1.463 3.538T4 19v-2q1.25 0 2.125-.875T7 14m1-2V8h8v4zm3 8v-6h2v6zm4-6h2q0 1.25.875 2.125T20 17v2q-2.075 0-3.537-1.463T15 14");
}

</style>
