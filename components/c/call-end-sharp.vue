<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0ea2qtkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:call-end-sharp" /></template>
<style>
.n0ea2qtkg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5c3.6 0 6.9 1.2 8.65 3.05l.963 1.05l-.963 1.05l-1.55 1.65l-.523.56l-.677-.36l-2.6-1.3l-.554-.279l.004-.621v-1.9A12 12 0 0 0 12 11a12 12 0 0 0-2.75.4v1.9l.004.621l-.554.279l-2.6 1.3l-.677.36l-.523-.56l-1.55-1.65l-.963-1.05l.963-1.05C5.1 9.7 8.4 8.5 12 8.5Zm0 5.5v5.5m-2.25-2.25L12 19.5l2.25-2.25");
}

</style>
