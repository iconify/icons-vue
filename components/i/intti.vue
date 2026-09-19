<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z6hqog0yt"/><path class="mzz9pwbyi"/><rect class="kc0nl3bdm"/><path class="iv6vnjb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:intti" /></template>
<style>
.iv6vnjb2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.605 28.946h18.79");
}

.kc0nl3bdm {
  width: 37.186px;
  height: 7.865px;
  x: 5.407px;
  y: 31.773px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.096px;
}

.mzz9pwbyi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.612 19.908v-8.766l5.807 8.766v-8.766");
}

.z6hqog0yt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.295 8.362H7.705L4.5 11.568v7.915l3.205 3.205h32.59l3.205-3.205v-7.915zm-4.674 2.78v8.766m-23.242-8.766v8.766m10.061-8.766h5.808m-2.904 8.766v-8.766m5.147 0h2.904m-2.904 8.766v-8.766");
}

</style>
