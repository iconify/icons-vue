<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0iflzkqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-off-sharp" /></template>
<style>
.w0iflzkqp {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 2L14 2L20 8L20 15.3431M14 2L14 8L20 8M4 4L4 22L20 22L20 20M1.7071 1.7071L22.2929 22.2929");
}

</style>
