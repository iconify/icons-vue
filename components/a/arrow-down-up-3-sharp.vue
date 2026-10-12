<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3f82daqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-up-3-sharp" /></template>
<style>
.o3f82daqf {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 10L7 11L7 21.2604L7 21.9144M12.3005 16.8112L12 17.1053L7 22L2 17.1053L1.6995 16.8112M17 14L17 13L17 2.7396L17 2.0856M11.6995 7.1888L12 6.8947L17 2L22 6.8947L22.3005 7.1888");
}

</style>
