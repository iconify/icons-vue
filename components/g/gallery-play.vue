<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc-_4xbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-play" /></template>
<style>
.bc-_4xbar {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3H19M5 7H19C20.1046 7 21 7.9 21 9V19C21 20.1 20.1046 21 19 21H5C3.8954 21 3 20.1 3 19V9C3 7.9 3.8954 7 5 7ZM9.5 11.77C9.5 11.17 10.1106 10.8 10.5813 11.12L14.3339 13.67C14.5554 13.82 14.5554 14.18 14.3339 14.33L10.5813 16.88C10.1106 17.2 9.5 16.83 9.5 16.23V11.77Z");
}

</style>
