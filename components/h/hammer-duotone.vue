<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="g9l-_mb0g"/><path class="gce9d1a7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hammer-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g9l-_mb0g {
  d: path("M245.66 129L217 157.66a8 8 0 0 1-11.3 0L168.1 120l-28 28l-32-32l28-28L80 31.78a87.81 87.81 0 0 1 98.31 18l67.35 67.89a8 8 0 0 1 0 11.33");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gce9d1a7u {
  d: path("m251.34 112l-67.46-67.92a96.1 96.1 0 0 0-135.77 0l-.09.09L34.25 58.4a8 8 0 0 0 11.49 11.13l13.73-14.18a80 80 0 0 1 18.71-13.9L124.68 88l-96 96a16 16 0 0 0 0 22.63l20.69 20.69a16 16 0 0 0 22.63 0l96-96l14.34 14.34L200 163.3a16 16 0 0 0 22.63 0l28.69-28.69a16 16 0 0 0 .02-22.61M60.68 216L40 195.31l68-68L128.68 148Zm101.66-101.68L140 136.67L119.31 116l22.35-22.35a8 8 0 0 0 0-11.32L94.32 35a80 80 0 0 1 78.23 20.41l44.22 44.51L188 128.66l-14.34-14.34a8 8 0 0 0-11.32 0m49 37.66l-12-12L228 111.25l12 12Z");
}

</style>
