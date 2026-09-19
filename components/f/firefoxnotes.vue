<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g9n_-1q6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:firefoxnotes" /></template>
<style>
.g9n_-1q6p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.64 4.51a2.6 2.6 0 0 0-2.78 2.78h-2.78a2.59 2.59 0 0 0-2.79 2.79v30.63a2.59 2.59 0 0 0 2.79 2.78h27.84a2.59 2.59 0 0 0 2.79-2.78V10.08a2.59 2.59 0 0 0-2.79-2.79h-2.78c0-3.71-5.57-3.71-5.57 0H18.43a2.6 2.6 0 0 0-2.79-2.78m-2.79 9.54h22.3m-22.3 7.49h22.3m-22.3 7.49h22.3m-22.3 7.5h22.3");
}

</style>
