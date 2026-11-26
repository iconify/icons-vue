<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh1nlxbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-wrap-left-sharp" /></template>
<style>
.lh1nlxbwx {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7L13 7L13 17L3 17ZM2 3L22 3M2 21L22 21M16 9L22 9M16 15L22 15");
}

</style>
