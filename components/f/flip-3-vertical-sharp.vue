<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0szq6bvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flip-3-vertical-sharp" /></template>
<style>
.d0szq6bvk {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 22L5 2M1.7071 18.7071L5 22L8.2929 18.7071M1.7071 5.2929L5 2L8.2929 5.2929M11 14L22 14L22 22ZM11 10L22 10L22 2Z");
}

</style>
