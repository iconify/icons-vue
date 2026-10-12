<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mno6xf-fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:histogram" /></template>
<style>
.mno6xf-fu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 17.75v-5.5h4v-6h4v-2.5h4v6h4v8Zm4-5.5v5.5m4-11.5v11.5m4-8v8m-13.25 3h18.5");
}

</style>
