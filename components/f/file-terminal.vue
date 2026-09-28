<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj7rkf1nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-terminal" /></template>
<style>
.gj7rkf1nk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 2H8C5.79086 2 4 3.79086 4 6V18C4 20.2091 5.79086 22 8 22H16C18.2091 22 20 20.2091 20 18V8L14 2ZM14 2V5C14 6.65685 15.3431 8 17 8H20M8 11L11.0571 13.6204C11.1679 13.7154 11.2317 13.854 11.2317 14C11.2317 14.146 11.1679 14.2846 11.0571 14.3796L8 17M13 18L16 18");
}

</style>
