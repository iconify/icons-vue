<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1ncy95lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fast-forward" /></template>
<style>
.x1ncy95lk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 7.504963C2 6.190024 3.571571 5.511488 4.52863 6.413212L9.685754 11.272166C10.10475 11.666937 10.10475 12.333063 9.685754 12.727834L4.52863 17.586788C3.571571 18.488512 2 17.809976 2 16.495037ZM14 7.504963C14 6.190024 15.571571 5.511488 16.52863 6.413212L21.685754 11.272166C22.10475 11.666937 22.10475 12.333063 21.685754 12.727834L16.52863 17.586788C15.571571 18.488512 14 17.809976 14 16.495037Z");
}

</style>
