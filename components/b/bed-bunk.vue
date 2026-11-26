<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz4bf4tld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bed-bunk" /></template>
<style>
.vz4bf4tld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3V5M3 5V7V9M3 5H7C8.1046 5 9 5.8954 9 7V9M3 9V13M3 9H9M3 13V15V17M3 13H7C8.1046 13 9 13.8954 9 15V17M3 17V21M3 17H9M9 9H16M16 9H21M16 9V13M21 9V5V3M21 9V13M9 17H16M16 17H21M16 17V13M16 17V20V21M21 17V13M21 17V21M16 13H21");
}

</style>
