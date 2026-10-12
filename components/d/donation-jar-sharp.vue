<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="raekmjbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:donation-jar-sharp" /></template>
<style>
.raekmjbxr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25v7.5m3-6.5h2.5l2.1-1.1l.443-.245l.507-.005h3.95v3H11.5m-5.75 4.35h6.6l1.037-.005l.813-.645l5.6-4.4l1.099-1.014l-1.85-2.35l-1.099 1.014l-3.2 2.5m-1.25-4.84h-.275l-.185-.17c-1.39-1.15-3.22-2.62-3.22-4.59V3.69h2.95l.73.92l.717-.92h2.953v2.06c0 1.97-1.83 3.44-3.21 4.6l-.221.17H13.5Z");
}

</style>
