<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqc-6obkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flag-swallowtail" /></template>
<style>
.aqc-6obkw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 2L4 22M4 4L18.9983 4C19.797 4 20.2734 4.8901 19.8303 5.5547L17.0517 9.7226C16.9398 9.8906 16.9398 10.1094 17.0517 10.2774L19.8303 14.4453C20.2734 15.1099 19.797 16 18.9983 16L4 16");
}

</style>
