<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6lzy44hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cargo-plane-sharp" /></template>
<style>
.e6lzy44hr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5.5h1l.42.62l2.16 3.26l.42.62h8.75v4.5h-2l-.39.64l-2.72 4.47l-.39.64H8.5l.16-.73l.93-4.29l.16-.73H5l-.41-.63l-1.43-2.24l-.41-.63V5.5zm14.05 2.81l1.9-4.37l.3-.69l.22.72l1.06 3.56l.22.72l-.74.14l-2.52.47l-.74.14z");
}

</style>
