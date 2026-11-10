<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc761bc2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:a-text-cursor-sharp-two-tone" /></template>
<style>
.rc761bc2t {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.93 18.6273L7.002 6L12.074 18.6273M4.19 13H9.813M19.002 6.8C18.668 6.35 17.602 5 16.002 5H15.002M19.002 6.8C19.335 6.35 20.402 5 22.002 5H23.002M19.002 6.8V17.2M19.002 17.2C19.335 17.65 20.402 19 22.002 19H23.002M19.002 17.2C18.668 17.65 17.602 19 16.002 19H15.002");
}

</style>
