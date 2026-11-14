<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="flpjlz-1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aircraft-rudder" /></template>
<style>
.flpjlz-1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 16l7-13.5h4V16Zm8-13.5V16m4.75 3h6.25m-4.25-2l-2 2l2 2m2.25-4l2 2l-2 2");
}

</style>
