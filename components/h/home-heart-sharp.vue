<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0xu-6j2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-heart-sharp" /></template>
<style>
.a0xu-6j2k {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 10L12 2.9963L3 10L3 21L21 21ZM12 17C10.4032 15.7011 8.5 14.5833 8.5 12.9167C8.5 11.8581 9.4402 11 10.6 11C11.125 11 11.5949 11.182 12 11.5C12.4051 11.182 12.875 11 13.4 11C14.5598 11 15.5 11.8581 15.5 12.9167C15.5 14.5833 13.5968 15.7011 12 17Z");
}

</style>
