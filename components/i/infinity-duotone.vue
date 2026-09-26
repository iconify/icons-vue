<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljr8ztagt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:infinity-duotone" /></template>
<style>
.ljr8ztagt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.3333 9.0186C16.0667 8.3626 17.0161 8 18 8C20.2091 8 22 9.7909 22 12C22 14.2091 20.2091 16 18 16C17.0161 16 16.0667 15.6374 15.3333 14.9814L8.6667 9.0186C7.9333 8.3626 6.9839 8 6 8C3.7909 8 2 9.7909 2 12C2 14.2091 3.7909 16 6 16C6.9839 16 7.9333 15.6374 8.6667 14.9814Z");
}

</style>
