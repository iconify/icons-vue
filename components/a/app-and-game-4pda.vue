<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f2h22kbsz"/><path class="xrj_4ib6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:app-and-game-4pda" /></template>
<style>
.f2h22kbsz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.099 36.501v-25l-13.29 16.666h16.382");
}

.xrj_4ib6k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.857 40.438A21.5 21.5 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24a21.5 21.5 0 0 1 4.664-13.37m2.572-2.717A21.5 21.5 0 0 1 24 2.5c11.874 0 21.5 9.626 21.5 21.5h0a21.5 21.5 0 0 1-5.002 13.786");
}

</style>
