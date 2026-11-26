<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv67yeehl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-wrap-right-sharp" /></template>
<style>
.qv67yeehl {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 7L21 7L21 17L11 17ZM2 3L22 3M2 21L22 21M2 9L8 9M2 15L8 15");
}

</style>
