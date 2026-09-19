<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m05e4bcnb"/><path class="eexc16o0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-alien-monster" /></template>
<style>
.eexc16o0h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.308 30.762v4.27h-4.27v-4.27m19.924 0h4.269v-4.27m-8.539 4.27v4.27h4.27v-4.27m-15.654 0h11.384m-8.538-17.795h4.98M9.77 16.526h4.268m19.212 0h4.98m-21.932 4.271h2.561v4.27h-2.561zM9.77 35.033h4.268v4.27H9.77zm24.192 0h4.269v4.27h-4.27zm-4.679-14.236h2.562v4.27h-2.562z");
}

.m05e4bcnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.039 30.762h-4.27v-4.27m4.684-9.966v-3.559h2.432m16.157 3.559v-3.559h-2.43M7.635 23.644H5.5V12.967h4.27v10.677m28.46 0V12.967h4.27v10.677h-2.135m-23.48-10.677v-4.27h4.269v4.27m4.981 0v-4.27h4.269v4.27M9.77 23.644h2.134v2.136h-4.27v-2.136m32.731 0v2.136h-4.269v-2.136h2.135");
}

</style>
