<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7u8jubac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dress-sharp" /></template>
<style>
.j7u8jubac {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 10L5.5 3L8.5 2V2.5C8.5 4.43 10.067 6 12 6C13.933 6 15.5 4.43 15.5 2.5V2L18.5 3L16.5 10M7.5 10L4 22H20L16.5 10M7.5 10H16.5");
}

</style>
