<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyxcyacjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:helicopter" /></template>
<style>
.lyxcyacjk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 6L21 6M14 6L14 10M21.5207 14L16.5207 14M7 10L17.4793 10C18.5511 10 19.5414 10.5718 20.0773 11.5L21.6651 14.25C21.8845 14.63 22 15.0612 22 15.5C22 16.8807 20.8807 18 19.5 18L12.7735 18C12.059 18 11.3988 17.6188 11.0415 17L7 10ZM2 10L7 10M2 7L2 13");
}

</style>
