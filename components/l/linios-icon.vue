<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dj0go9jyw"/><path class="tllj2xdhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:linios-icon" /></template>
<style>
.dj0go9jyw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.59 10.325c7.552 9.162 6.247 22.712-2.915 30.265c-9.162 7.552-22.712 6.247-30.265-2.915c-7.552-9.162-6.247-22.713 2.915-30.265a21.5 21.5 0 0 1 27.219-.107");
}

.tllj2xdhe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.813 34.285c-5.705-7.262-4.443-17.775 2.819-23.48s17.774-4.443 23.48 2.819s4.443 17.774-2.82 23.48a16.72 16.72 0 0 1-20.66 0");
}

</style>
