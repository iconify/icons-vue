<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdv4d22pr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:expand-dashed-up-left-box-sharp-fill" /></template>
<style>
.qdv4d22pr {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 18L3 18M6.2929 14.7071L3 18L6.2929 21.2929M18 14L18 3M21.2929 6.2929L18 3L14.7071 6.2929M3 9L3 5M5 3L9 3M11 5L11 9M5 11L9 11");
}

</style>
