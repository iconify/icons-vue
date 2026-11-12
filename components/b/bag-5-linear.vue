<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="azapv0b9g"/><path class="ajlov99ys"/><path class="q3qht7o9s"/><path class="e_un4ubpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-5-linear" /></template>
<style>
.ajlov99ys {
  d: path("M9 6.5V5.5C9 3.84315 10.3431 2.5 12 2.5C13.6569 2.5 15 3.84315 15 5.5V6.5");
}

.azapv0b9g {
  d: path("M11.1481 6.5H12.851C16.7834 6.5 18.7496 6.5 19.9152 7.63836C20.1262 7.84447 20.3138 8.0733 20.4745 8.32067C21.3622 9.68686 20.9766 11.6149 20.2054 15.4709C19.6682 18.1567 19.3996 19.4996 18.5122 20.3646C18.3482 20.5244 18.1707 20.6699 17.9818 20.7994C16.9596 21.5 15.5901 21.5 12.851 21.5H11.1481C8.40907 21.5 7.03956 21.5 6.01737 20.7994C5.82845 20.6699 5.651 20.5244 5.48697 20.3646C4.5995 19.4996 4.33092 18.1567 3.79375 15.4709C3.02255 11.6149 2.63695 9.68686 3.52461 8.32067C3.68534 8.0733 3.87293 7.84447 4.08398 7.63836C5.24955 6.5 7.21574 6.5 11.1481 6.5Z");
}

.e_un4ubpg {
  stroke-linejoin: round;
  d: path("M15 10.5H15.0001");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q3qht7o9s {
  stroke-linejoin: round;
  d: path("M9 10.5H9.0001");
}

</style>
