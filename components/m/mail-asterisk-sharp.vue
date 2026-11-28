<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w812iypoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-asterisk-sharp" /></template>
<style>
.w812iypoy {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 20L2 20L2 4L22 4L22 11M2 7L11.2929 11C11.7154 11.2817 12.2846 11.2817 12.7071 11L22 7M19 13.5L19 20.5M16.2 19.1L21.8 14.9M16.2 14.9L21.8 19.1");
}

</style>
