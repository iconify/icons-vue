<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9z9lsbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-check-corner" /></template>
<style>
.t9z9lsbhf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 19H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v4M4 6l4 4c.64.64 1.36 1 2 1h4c.64 0 1.36-.36 2-1l4-4m-5 12l2 2l4-4");
}

</style>
