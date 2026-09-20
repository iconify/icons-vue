<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="noe7scbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:healthmate" /></template>
<style>
.noe7scbiy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.63 7.15a10.12 10.12 0 0 0-7.86 16.51L24 42.71l16.07-18.86l.08-.09l.08-.1A10.13 10.13 0 1 0 24 11.58a10.1 10.1 0 0 0-8.36-4.43Zm2.18 11.68l6.18-7.25");
}

</style>
