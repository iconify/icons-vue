<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yz-5grpvx"/><path class="rz8ki9vyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:landsbanken" /></template>
<style>
.rz8ki9vyk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.572 25.572l2.075 3.557l-4.118.017l-4.12.018l2.046-3.574l2.043-3.576Z");
}

.yz-5grpvx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.405 13.72l-3.071-5.318H12.557l3.06 5.301Zm1.295 2.025l14.8 23.821H26.194l2.943-5.097H15.048l-2.961 5.129H4.5L14.617 21.07l-3.316-5.348Z");
}

</style>
