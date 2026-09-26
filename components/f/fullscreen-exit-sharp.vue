<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pu3p-s68u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fullscreen-exit-sharp" /></template>
<style>
.pu3p-s68u {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 10L14 10L14 2M14.1757 9.8243L21.2929 2.7071M2 14L10 14L10 22M9.8243 14.1757L2.7071 21.2929");
}

</style>
