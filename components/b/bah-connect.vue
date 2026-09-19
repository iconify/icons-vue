<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xg0-ufbga"/><path class="qqqqhccti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bah-connect" /></template>
<style>
.qqqqhccti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.895 23.362v5.04h-5.04v5.181h5.04v5.04h5.182v-5.04h5.041v-5.181h-5.041v-5.04z");
}

.xg0-ufbga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.77 43.045c-6.537 1.004-12.65-3.48-13.653-10.017c-.849-5.528 2.248-10.716 7.15-12.847c2.14-.93 3.248-1.518 4.557-2.49c3.529-2.617 4.917-7.686 2.334-13.138c-3.33 1.75-5.572 2.584-8.648 6.15c-1.208-1.74-2.41-3.163-3.85-4.237c-2.566 3-4.085 6.293-4.77 9.605c-1.838-1.136-3.688-1.825-5.457-2.147c-.4 3.325-1.055 6.554.045 10.723c-2.228-.094-3.776.116-5.597.667C9.04 33.358 19.674 45.847 35.77 43.046Z");
}

</style>
