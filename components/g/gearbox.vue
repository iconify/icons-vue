<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8zpnkzrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gearbox" /></template>
<style>
.e8zpnkzrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 2V12M4 12V22M4 12H12M20 2V12M20 12V22M20 12H12M12 8V12M12 8C13.657 8 15 6.657 15 5C15 3.343 13.657 2 12 2C10.343 2 9 3.343 9 5C9 6.657 10.343 8 12 8ZM12 12V22");
}

</style>
