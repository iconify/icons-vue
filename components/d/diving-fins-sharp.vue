<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf6s2bcfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:diving-fins-sharp" /></template>
<style>
.bf6s2bcfg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 2.75h3l-.02.75l-.46 17l-.02.75l-.74-.1l-6.02-.8l-.74-.1l.18-.73L6.82 3.48L7 2.75zm8.5 0h-3l.02.75l.46 17l.02.75l.74-.1l6.02-.8l.74-.1l-.18-.73l-3.89-16.04l-.18-.73zM8 9l-1.25 9.5M16 9l1.25 9.5");
}

</style>
