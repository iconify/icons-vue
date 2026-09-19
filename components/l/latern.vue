<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q67sracfw"/><path class="dilxt6a9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:latern" /></template>
<style>
.dilxt6a9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.332 17.863a25.43 25.43 0 0 1 19.026-.324M23.888 43.5l.012-27.646m-2.104-7.862a2.328 2.328 0 1 1 4.032 0");
}

.q67sracfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.022 14.417c.425 7.969 4.378 28.945 9.718 29.082c5.354.138 7.551-15.6 10.239-29.157l-5.342-1.929l.074-2.893l-4.896-2.597l-4.897 2.968l.074 2.893Z");
}

</style>
