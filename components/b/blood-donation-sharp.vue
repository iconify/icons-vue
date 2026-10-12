<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i75-oxn6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:blood-donation-sharp" /></template>
<style>
.i75-oxn6u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.75v7.5m3-6.5h2.5l2.1-1.1l.443-.245l.507-.005h3.95v3H11.5m-5.75 4.35h6.6l1.037-.005l.813-.645l5.6-4.4l1.099-1.014l-1.85-2.35l-1.099 1.014l-3.2 2.5M13.5 2.75c1.1 1.6 3 3.4 3 5.25a3 3 0 0 1-6 0c0-1.85 1.9-3.65 3-5.25Z");
}

</style>
