<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jkkdspb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-desktop-computer" /></template>
<style>
.jkkdspb8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.571 33.53H8.43a2.93 2.93 0 0 1-2.93-2.927V10.475a2.93 2.93 0 0 1 2.929-2.928H39.57a2.93 2.93 0 0 1 2.93 2.928v20.128a2.93 2.93 0 0 1-2.93 2.927m-11.585 0v2.86c0 2.861 5.14 4.063 5.14 4.063h-18.25s5.102-1.202 5.102-4.062v-2.86M5.5 29.2h37");
}

</style>
