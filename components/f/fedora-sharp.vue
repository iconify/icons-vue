<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy_upbbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fedora-sharp" /></template>
<style>
.dy_upbbxv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 13l.75-5.5l.278-2.152L9.65 5.8l2.35.7l2.35-.7l2.122-.452l.278 2.152l.75 5.5Zm.5-2.5h10m-14.25 6v-1.85l2 .7C7 16.1 9.25 16.5 12 16.5s5-.4 7.25-1.15l2-.7v1.85c0 2-4.1 3.5-9.25 3.5s-9.25-1.5-9.25-3.5Z");
}

</style>
