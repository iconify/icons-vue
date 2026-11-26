<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv-kt6r5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:letter-spacing-fill" /></template>
<style>
.kv-kt6r5r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4V20M22 4V20M7 18L8.7857 13L11.0583 6.668C11.3743 5.783 12.6257 5.783 12.9417 6.668L15.2143 13L17 18M15.2143 13H8.7857");
}

</style>
