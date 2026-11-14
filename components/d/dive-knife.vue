<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li70erbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dive-knife" /></template>
<style>
.li70erbzz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.718 5.282l-.354 3.182L12 14.828L9.172 12l6.364-6.364ZM8.111 10.939l4.95 4.95m-3.713-3.712l2.475 2.475l-5.303 5.303l-2.475-2.475Zm6.895-4.42l-3.889 3.889");
}

</style>
