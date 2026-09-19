<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g5f_9sb8l"/><path class="tnjn_mvmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fantop" /></template>
<style>
.g5f_9sb8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.502a4 4 0 0 0-2.828 1.172l-11.5 11.5A4 4 0 0 0 8.5 21.002v6a4 4 0 0 0 1.172 2.828l11.5 11.5a4 4 0 0 0 5.656 0l11.5-11.5a4 4 0 0 0 1.172-2.828v-6a4 4 0 0 0-1.172-2.828l-11.5-11.5A4 4 0 0 0 24 5.502");
}

.tnjn_mvmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.5 21l9.5-9.498L33.5 21M24 21l-4.749-4.75");
}

</style>
