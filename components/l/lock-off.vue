<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be6x86cwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lock-off" /></template>
<style>
.be6x86cwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 10L7.5 7.5M8.8974 3.2406C9.7047 2.4719 10.7973 2 12 2C14.4853 2 16.5 4.0147 16.5 6.5L16.5 10M10 10L7 10C5.3431 10 4 11.3431 4 13L4 19C4 20.6569 5.3431 22 7 22L17 22C18.3538 22 19.4981 21.1033 19.8715 19.8715M20 14.3431L20 13C20 11.3431 18.6569 10 17 10L15.6569 10M2 2L22 22");
}

</style>
