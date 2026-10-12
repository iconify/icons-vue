<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-hojpwbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bell-off" /></template>
<style>
.k-hojpwbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25a6 6 0 0 0-6 6v3.6c0 .7-.25 1.4-.7 1.95l-.6.75c-.6.75-.1 1.95.9 1.95h12.8c1 0 1.5-1.2.9-1.95l-.6-.75c-.45-.55-.7-1.25-.7-1.95v-3.6a6 6 0 0 0-6-6m-2.25 17c.55.6 1.3.95 2.25.95s1.7-.35 2.25-.95M3.75 3.75l16.5 16.5");
}

</style>
