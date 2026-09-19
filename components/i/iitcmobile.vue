<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jvu-sacxk"/><path class="jy91g4bkn"/><path class="dm0_j0b8x"/><path class="sdmg2cb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iitcmobile" /></template>
<style>
.dm0_j0b8x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.978 32.925l8.043-4.644V10.124");
}

.jvu-sacxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.077 9.009l-2.446 1.412v18.5l9.944 5.741");
}

.jy91g4bkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.021 15.093l-8.042 4.644v18.157m-14.056 1.115l2.446-1.412v-18.5l-9.944-5.741");
}

.sdmg2cb0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.978 14.75v18.5L24 42.5l16.021-9.25v-18.5L24 5.5z");
}

</style>
