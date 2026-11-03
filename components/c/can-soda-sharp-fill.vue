<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s3akf14aj"/><path class="vwviy_bdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:can-soda-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s3akf14aj {
  fill: currentColor;
  d: path("M16 8.0001L17.4 9.8667L17.8 10.4001C17.9298 10.5732 18 10.7838 18 11.0001L18 20C18 20.2652 17.8946 20.5196 17.7071 20.7071L15.7071 22.7071C15.5196 22.8946 15.2652 23 15 23L9 23C8.7348 23 8.4804 22.8946 8.2929 22.7071L6.2929 20.7071C6.1054 20.5196 6 20.2652 6 20L6 11.0001C6 10.7838 6.0702 10.5732 6.2 10.4001L6.6 9.8667L8 8.0001L6 8.0001L6 6.0001L9.9882 6.0001C9.9921 6 9.9961 6 10 6L14 6C14.0039 6 14.0079 6 14.0118 6.0001L18 6.0001L18 8.0001L16 8.0001Z");
  stroke: none;
}

.vwviy_bdk {
  d: path("M16.2913 1.5145L13 7");
}

</style>
