<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wv1wny3lr"/><path class="x4g4x6bkp"/><path class="og2bie__m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:home-abc-launcher" /></template>
<style>
.og2bie__m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.468 16.333h3.687v3.687h-3.687zm6.689 0h3.687v3.687h-3.687zm6.689 0h3.687v3.687h-3.687zm-13.378 6.713h3.687v3.687h-3.687zm6.689 0h3.687v3.687h-3.687zm6.689 0h3.687v3.687h-3.687zm-13.378 6.712h3.687v3.687h-3.687zm6.689 0h3.687v3.687h-3.687zm6.689 0h3.687v3.687h-3.687zM15.468 36.47h3.687v3.687h-3.687zm6.689 0h3.687v3.687h-3.687zm6.689 0h3.687v3.687h-3.687z");
}

.wv1wny3lr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.578 18.078L24 3.5L9.422 18.078");
}

.x4g4x6bkp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.86 5.364c9.961.943 17.751 9.328 17.751 19.525C43.611 35.718 34.83 44.5 24 44.5S4.389 35.718 4.389 24.889c0-5.582 2.332-10.593 6.065-14.166v-6.35h5.012V7.25a19.4 19.4 0 0 1 6.66-1.873");
}

</style>
