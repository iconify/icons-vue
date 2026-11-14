<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfkz-9bjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:control-group" /></template>
<style>
.dfkz-9bjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM2.5 20c0-3.75 2-6 4.5-6s4.5 2.25 4.5 6m1-16.75a2.75 2.75 0 0 1 0 5.5m3.5 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

</style>
