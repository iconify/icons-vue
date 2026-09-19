<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cwu3zabwn"/><path class="z985_ebil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gomining" /></template>
<style>
.cwu3zabwn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m44.885 16.833l-6.767 7.17l6.765 7.171A21.5 21.5 0 0 1 24.615 45.5c-11.874 0-21.5-9.626-21.5-21.5s9.626-21.5 21.5-21.5A21.5 21.5 0 0 1 44.06 14.83");
}

.z985_ebil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.761 16.833l-6.767 7.17l6.765 7.171");
}

</style>
