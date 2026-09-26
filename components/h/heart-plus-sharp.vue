<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkbveib8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heart-plus-sharp" /></template>
<style>
.kkbveib8h {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21.3876 11.6753L21.6195 11C21.8649 10.2852 22 9.538 22 8.75C22 5.5743 19.3138 3 16 3C14.5 3 13.1574 3.5459 12 4.5C10.8426 3.5459 9.5 3 8 3C4.6862 3 2 5.5743 2 8.75C2 13.75 7.4376 17.1033 12 21L12.2805 21.2396M19 14L19 22M15 18L23 18");
}

</style>
