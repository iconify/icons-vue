<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd4lemjwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:click-path" /></template>
<style>
.hd4lemjwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.5 10.5l10 4l-4 2l-2 4ZM2.5 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm9 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM3 12.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM7.25 4h.01m2.49 0h.01m.74 2.75h.01M8 9.25h.01M7.25 12h.01");
}

</style>
