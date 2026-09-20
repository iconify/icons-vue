<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pzvbot6iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-drop-up-outline-rounded" /></template>
<style>
.pzvbot6iw {
  fill: currentColor;
  d: path("M8.2 14q-.225 0-.362-.15T7.7 13.5q0-.05.15-.35l3.625-3.625q.125-.125.25-.175T12 9.3t.275.05t.25.175l3.625 3.625q.075.075.113.163t.037.187q0 .2-.137.35T15.8 14z");
}

</style>
