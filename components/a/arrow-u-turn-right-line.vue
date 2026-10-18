<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uuob3acrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-u-turn-right-line" /></template>
<style>
.uuob3acrc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 19L12 19C9.2386 19 7 16.7614 7 14C7 11.2386 9.2386 9 12 9L20 9M16 5L20.8123 8.6096C21.0625 8.8097 21.0625 9.1903 20.8123 9.3904L16 13M3 4L3 20");
}

</style>
