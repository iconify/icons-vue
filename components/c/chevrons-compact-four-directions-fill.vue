<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d74lekbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-compact-four-directions-fill" /></template>
<style>
.d74lekbjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 15L2.0733 12.22C1.9756 12.08 1.9756 11.92 2.0733 11.78L4 9M15 20L12.2236 21.93C12.0828 22.02 11.9172 22.02 11.7764 21.93L9 20M20 15L21.927 12.22C22.024 12.08 22.024 11.92 21.927 11.78L20 9M15 4L12.2236 2.07C12.0828 1.98 11.9172 1.98 11.7764 2.07L9 4");
}

</style>
