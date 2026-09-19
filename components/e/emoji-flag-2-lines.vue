<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="myh8k-ugx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-flag-2-lines" /></template>
<style>
.myh8k-ugx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 36.982v-23.74m-39-.5v23.74m39 .5c-2.459-.636-4.875-1.272-9.75-1.272c-8.478 0-11.022 2.543-19.5 2.543c-4.875 0-7.334-.635-9.75-1.271m39-24.239c-2.459-.636-4.875-1.272-9.75-1.272c-8.478 0-11.022 2.543-19.5 2.543c-4.875 0-7.334-.636-9.75-1.271M24 36.896V12.742");
}

</style>
