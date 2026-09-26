<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="comqdxbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heart-plus" /></template>
<style>
.comqdxbqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21.6195 11C21.8649 10.2852 22 9.538 22 8.75C22 5.5743 19.3138 3 16 3C14.5 3 13.1574 3.5459 12 4.5C10.8426 3.5459 9.5 3 8 3C4.6862 3 2 5.5743 2 8.75C2 13.75 7.4376 17.1033 12 21M19 15V21M16 18H22");
}

</style>
