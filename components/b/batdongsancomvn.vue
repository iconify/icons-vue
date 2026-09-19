<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vk7a09btd"/><path class="pqwinkapu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:batdongsancomvn" /></template>
<style>
.pqwinkapu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.1 16.02a2.68 2.68 0 0 1 3.8 0l15.194 15.195a2.68 2.68 0 0 1 0 3.798l-5.698 5.698a2.68 2.68 0 0 1-3.798 0m-15.195 0l5.698-5.698a2.68 2.68 0 0 1 3.798 0l5.698 5.698m-15.195 0a2.68 2.68 0 0 1-3.798 0l-5.698-5.698a2.68 2.68 0 0 1 0-3.798L22.101 16.02a2.68 2.68 0 0 1 3.798 0m3.678-5.052V9.42c0-2.686 3.799-2.686 3.799 0v5.346");
}

.vk7a09btd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.1 7.29a2.68 2.68 0 0 1 3.8 0l15.194 15.194a2.68 2.68 0 0 1 0 3.798l-5.698 5.698a2.68 2.68 0 0 1-3.798 0m-15.195 0l5.698-5.698a2.68 2.68 0 0 1 3.798 0l5.698 5.698m-15.195 0a2.68 2.68 0 0 1-3.798 0l-5.698-5.698a2.68 2.68 0 0 1 0-3.798L22.101 7.289a2.68 2.68 0 0 1 3.798 0");
}

</style>
