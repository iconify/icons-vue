<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chgn2-bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:angle-sharp" /></template>
<style>
.chgn2-bgj {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 21L3 21L11.6523 2.4222M6.4082 12.9502C9.4572 14.4747 11.3832 17.5911 11.3832 21");
}

</style>
