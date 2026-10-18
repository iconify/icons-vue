<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y62srcczk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-checks-sharp-fill" /></template>
<style>
.y62srcczk {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.7071 6.7071L4 9L8.2929 4.7071M1.7071 16.7071L4 19L8.2929 14.7071M11 7L23 7M11 17L23 17");
}

</style>
