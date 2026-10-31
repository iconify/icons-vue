<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnea6j__l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caravan-sharp" /></template>
<style>
.wnea6j__l {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 18L2 18L2 4L19 4L19 18L10 18M10 18L10 8L15 8L15 18M2 8L6 8L6 12L2 12M10 18C10 19.1046 9.1046 20 8 20C6.8954 20 6 19.1046 6 18C6 16.8954 6.8954 16 8 16C9.1046 16 10 16.8954 10 18ZM19 14L23 14");
}

</style>
