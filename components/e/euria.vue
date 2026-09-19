<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d1ia-ufsz"/><path class="yll9dps0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:euria" /></template>
<style>
.d1ia-ufsz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.794 5.063C7.68 5.78 2.956 15.551 3 21.983s.87 17.554 16.587 21.036s22.352-5.68 24.62-13.337s-.109-19.265-10.004-23.08s-11.236-2.024-17.41-1.539Z");
}

.yll9dps0m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.352 17.326c1.462 2.637 5.011 11.543-1.767 17.582c-6.778 6.038-15.486 7.435-20.292 3.04s-6.408-14.953 1.56-19.554c7.97-4.6 15.282-10.474 20.499-1.068");
}

</style>
