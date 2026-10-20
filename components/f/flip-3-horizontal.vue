<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxd5rdj7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-3-horizontal" /></template>
<style>
.yxd5rdj7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 5L22 5M5 2L2 5L5 8M19 2L22 5L19 8M10 13.7712L10 21C10 21.5523 9.5523 22 9 22L3.0019 22C2.1551 22 1.6916 21.0132 2.2323 20.3614L8.2304 13.1327C8.8283 12.4121 10 12.8349 10 13.7712ZM14 13.7712L14 21C14 21.5523 14.4477 22 15 22L20.9981 22C21.8449 22 22.3084 21.0132 21.7677 20.3614L15.7696 13.1327C15.1717 12.4121 14 12.8349 14 13.7712Z");
}

</style>
