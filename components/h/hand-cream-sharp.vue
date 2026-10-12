<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qasqj5w9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-cream-sharp" /></template>
<style>
.qasqj5w9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.75v7.5m3-6.5h2.5l2.1-1.1l.443-.245l.507-.005h3.95v3H11.5m-5.75 4.35h6.6l1.037-.005l.813-.645l5.6-4.4l1.099-1.014l-1.85-2.35l-1.099 1.014l-3.2 2.5m-4-13.1H17l-.25.71L16 5.54l-.25.71h-4.5L11 5.54l-.75-2.08l-.25-.71zm2.75 5l1.25 1.471v.729a1.25 1.25 0 0 1-2.5 0v-.729z");
}

</style>
