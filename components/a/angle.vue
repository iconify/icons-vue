<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8kit8bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:angle" /></template>
<style>
.m8kit8bmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 21L4.0013 21C3.2579 21 2.7744 20.2177 3.1069 19.5528L11.3832 3M6.4082 12.9502C9.4572 14.4747 11.3832 17.5911 11.3832 21");
}

</style>
