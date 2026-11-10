<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0owf8dou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cross-duotone" /></template>
<style>
.g0owf8dou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 10.12V13.88C3 14.7 3.6716 15.38 4.5 15.38H7.125C7.9534 15.38 8.625 16.05 8.625 16.88V19.5C8.625 20.33 9.2966 21 10.125 21H13.875C14.7034 21 15.375 20.33 15.375 19.5V16.88C15.375 16.05 16.0466 15.38 16.875 15.38H19.5C20.3284 15.38 21 14.7 21 13.88V10.12C21 9.3 20.3284 8.62 19.5 8.62H16.875C16.0466 8.62 15.375 7.95 15.375 7.12V4.5C15.375 3.67 14.7034 3 13.875 3H10.125C9.2966 3 8.625 3.67 8.625 4.5V7.12C8.625 7.95 7.9534 8.62 7.125 8.62H4.5C3.6716 8.62 3 9.3 3 10.12Z");
}

</style>
