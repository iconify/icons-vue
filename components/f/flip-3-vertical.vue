<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zurcb0bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-3-vertical" /></template>
<style>
.zurcb0bzv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 22L5 2M2 19L5 22L8 19M2 5L5 2L8 5M13.7712 14L21 14C21.5523 14 22 14.4477 22 15L22 20.9981C22 21.8449 21.0132 22.3084 20.3614 21.7677L13.1327 15.7696C12.4121 15.1717 12.8349 14 13.7712 14ZM13.7712 10L21 10C21.5523 10 22 9.5523 22 9L22 3.0019C22 2.1551 21.0132 1.6916 20.3614 2.2323L13.1327 8.2304C12.4121 8.8283 12.8349 10 13.7712 10Z");
}

</style>
