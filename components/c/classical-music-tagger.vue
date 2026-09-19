<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nrk5tobyw"/><circle class="p0u4-8man"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:classical-music-tagger" /></template>
<style>
.nrk5tobyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.787 27.975v-4.43L33.212 9.161l4.35 4.403l-14.448 14.411Zm18.807-14.443l3.215-3.208a1.543 1.543 0 0 0 .003-2.183l-.003-.003l-2.192-2.186a1.55 1.55 0 0 0-2.19 0l-3.215 3.209m-9.867 25.302L15.308 42.5l-8.57-8.57l.111-7.926l7.926-.111zm-12.084 1.038l2.132-2.132m1.798-1.798l1.232-1.232m2.049 2.048l-1.999 1.998m-1.632 1.632l-1.531 1.532m2.048 2.048l5.162-5.162");
}

.p0u4-8man {
  cx: 9.596px;
  cy: 28.674px;
  r: 1.056px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
