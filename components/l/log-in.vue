<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_zfenbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:log-in" /></template>
<style>
.o_zfenbeh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 4L17 4C19.2091 4 21 5.7909 21 8L21 16C21 18.2091 19.2091 20 17 20L15 20M13.1214 12L3 12M8.0607 6.5L13.7266 11.6314C13.9454 11.8296 13.9454 12.1704 13.7266 12.3686L8.0607 17.5");
}

</style>
