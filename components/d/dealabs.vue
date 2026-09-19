<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bq36-wm_z"/><path class="hf56_zctc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dealabs" /></template>
<style>
.bq36-wm_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.23 35.05l3.926 7.45h27.939l3.675-7.45l-13.491-19.885V5.5h-8.004v9.514z");
}

.hf56_zctc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.376 30.048l-6.624 3.189l-19.661-6.549");
}

</style>
