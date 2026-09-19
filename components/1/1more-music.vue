<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xpd24ibbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:1more-music" /></template>
<style>
.xpd24ibbb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.324 32.571V4.5L15.677 20.144c3.748-.51 6.82-.145 7.1 3.833V43.5");
}

</style>
