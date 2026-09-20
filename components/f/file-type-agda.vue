<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m8t09lxvv"/><path class="u5myhsbfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-agda" /></template>
<style>
.m8t09lxvv {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M8.46 10.79a.61.61 0 0 1-.62.61a.61.61 0 0 1-.6-.61a.61.61 0 0 1 .6-.61a.61.61 0 0 1 .62.61m2.26 0a.61.61 0 0 1-.61.61a.61.61 0 0 1-.61-.61a.61.61 0 0 1 .61-.61a.61.61 0 0 1 .61.61");
}

.u5myhsbfe {
  fill: none;
  stroke: var(--svg-color--d2d2d2, #d2d2d2);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-82px, 0.82px);
  d: path("M25.06 4.67L16 13.73m13.6-6.8l-4.54 4.54m4.53-6.8L25.06 9.2M13.73 4.67L9.2 9.2M16 4.67L11.47 9.2m0-4.53L2.4 13.73h4.53v4.54c0 4.98 4.08 9.06 9.06 9.06s9.06-4.08 9.06-9.06v-4.54l4.53-4.53");
}

</style>
