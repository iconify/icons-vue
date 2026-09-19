<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="b8jos8bnw"/><path class="peonw4hrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-accessible-forward" /></template>
<style>
.b8jos8bnw {
  cx: 17px;
  cy: 4.54px;
  r: 2px;
  fill: currentColor;
}

.peonw4hrp {
  fill: currentColor;
  d: path("M14 17h-2c0 1.65-1.35 3-3 3s-3-1.35-3-3s1.35-3 3-3v-2c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5m3-3.5h-1.86l1.67-3.67C17.42 8.5 16.44 7 14.96 7h-5.2c-.81 0-1.54.47-1.87 1.2L7.22 10l1.92.53L9.79 9H12l-1.83 4.1c-.6 1.33.39 2.9 1.85 2.9H17v5h2v-5.5c0-1.1-.9-2-2-2");
}

</style>
