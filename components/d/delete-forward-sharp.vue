<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rvb0qhbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:delete-forward-sharp" /></template>
<style>
.rvb0qhbdx {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.293 8.71L10 12M10 12L6.707 15.29M10 12L6.707 8.71M10 12L13.293 15.29M22 12L15 4H2V20H15L22 12Z");
}

</style>
