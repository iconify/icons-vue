<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fd5ejpbjq"/><path class="rmzpdjkoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:booking" /></template>
<style>
.fd5ejpbjq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4l.001 33h33a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-5.617 28.907a2.47 2.47 0 0 1-2.464-2.476a2.47 2.47 0 0 1 2.464-2.475a2.475 2.475 0 0 1 0 4.951");
}

.rmzpdjkoq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.89 24.406a5 5 0 0 1 0 9.998h-8.249V14.407h8.25a5 5 0 0 1 0 9.998m-.001.001h-8.249");
}

</style>
