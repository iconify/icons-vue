<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aifeoxcub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freezeyou" /></template>
<style>
.aifeoxcub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 38.024c1.033-3.529 3.47-8.057 5.986-8.057c4.772 0 6.409 10.55 13.674 10.55c7.844 0 16.475-15.047 17.34-33.033");
}

</style>
