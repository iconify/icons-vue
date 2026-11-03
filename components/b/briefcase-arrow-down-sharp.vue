<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfxp6dbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:briefcase-arrow-down-sharp" /></template>
<style>
.nfxp6dbnp {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9L12 14M8.7071 10.7071L12 14L15.2929 10.7071M2 22L22 22M8.5 6L3 6L3 18L21 18L21 6L15.5 6M8.5 6L8.5 2L15.5 2L15.5 6M8.5 6L15.5 6");
}

</style>
