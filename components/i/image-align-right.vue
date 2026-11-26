<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okca00ghk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-align-right" /></template>
<style>
.okca00ghk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 7L19 7C20.1046 7 21 7.8954 21 9L21 15C21 16.1046 20.1046 17 19 17L13 17C11.8954 17 11 16.1046 11 15L11 9C11 7.8954 11.8954 7 13 7ZM3 3H21M3 21H21");
}

</style>
