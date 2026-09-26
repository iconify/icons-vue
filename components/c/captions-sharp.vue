<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkyfztrvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:captions-sharp" /></template>
<style>
.vkyfztrvy {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4L22 4L22 20L2 20L2 4ZM10.8 10.6L10 10C9.5673 9.6754 9.0409 9.5 8.5 9.5C7.1193 9.5 6 10.6193 6 12C6 13.3807 7.1193 14.5 8.5 14.5C9.0409 14.5 9.5673 14.3246 10 14L10.8 13.4M18.8 10.6L18 10C17.5673 9.6754 17.0409 9.5 16.5 9.5C15.1193 9.5 14 10.6193 14 12C14 13.3807 15.1193 14.5 16.5 14.5C17.0409 14.5 17.5673 14.3246 18 14L18.8 13.4");
}

</style>
