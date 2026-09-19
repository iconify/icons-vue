<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d6l9nub5n"/><path class="h45czf9cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:admission-assistant" /></template>
<style>
.d6l9nub5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.728 43.5h26.239L24 14.112m-4.003 6.933L7.033 43.5m20.894-8.719l-7.93-13.736m0 13.736l3.965-6.868m3.965 6.868h-7.93M13.691 7.854L24.133 4.5l9.37 3.354l-4.115 1.66v4.598a9.52 9.52 0 0 0-5.72-1.625c-3.719 0-4.998 1.383-4.998 1.383V9.86Z");
}

.h45czf9cw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.303 8.891a19.3 19.3 0 0 0-4.633.968m-2.901-1.168v4.625");
}

</style>
