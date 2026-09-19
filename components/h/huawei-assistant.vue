<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="b16-ne0ni"/><path class="s3ze9qbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huawei-assistant" /></template>
<style>
.b16-ne0ni {
  cx: 27.121px;
  cy: 17.107px;
  r: 12.607px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s3ze9qbit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.975 29.662L14.73 42.234a3.68 3.68 0 0 1-5.965-4.255l7.78-14.007m15.777-12.13a7.204 7.204 0 0 1-.026 9.982m-14.015 9.92l-2.009 3.043");
}

</style>
