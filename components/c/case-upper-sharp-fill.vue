<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r85u4m2no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:case-upper-sharp-fill" /></template>
<style>
.r85u4m2no {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.93 18.63L7.002 6L12.074 18.63M4.19 13H9.813M15.945 18.67L19.002 10L22.059 18.67M16.886 16H21.118");
}

</style>
