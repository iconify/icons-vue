<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yvzehij8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:color-picker" /></template>
<style>
.yvzehij8v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.657 3.515l2.828 2.828l-3.535 3.536l-2.829-2.829Zm-4.95 2.828l4.95 4.95m-3.536-3.536l2.122 2.122l-4.597 4.596l-2.828.707l.707-2.828ZM2.75 19a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

</style>
