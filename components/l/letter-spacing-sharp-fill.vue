<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0iui48jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:letter-spacing-sharp-fill" /></template>
<style>
.n0iui48jv {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.928 18.6273L12 6L17.072 18.6273M9.188 13L14.812 13M2 3L2 21M22 3L22 21");
}

</style>
