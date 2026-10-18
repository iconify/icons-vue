<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5eqsabck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:brace-right-fill" /></template>
<style>
.z5eqsabck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 2C11.1046 2 12 2.8954 12 4L12 8.9645C12 9.4949 12.2107 10.0036 12.5858 10.3787L13.8536 11.6464C13.9473 11.7402 14 11.8674 14 12C14 12.1326 13.9473 12.2598 13.8536 12.3536L12.5858 13.6213C12.2107 13.9964 12 14.5051 12 15.0355L12 20C12 21.1046 11.1046 22 10 22");
}

</style>
