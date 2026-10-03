<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr8bhf-rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clipboard-type" /></template>
<style>
.wr8bhf-rd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 4C5.3431 4 4 5.3431 4 7L4 19C4 20.6569 5.3431 22 7 22L17 22C18.6569 22 20 20.6569 20 19L20 7C20 5.3431 18.6569 4 17 4M7 4C7 2.8954 7.8954 2 9 2L15 2C16.1046 2 17 2.8954 17 4L17 5C17 6.1046 16.1046 7 15 7L9 7C7.8954 7 7 6.1046 7 5L7 4ZM8 14L8 13C8 12.4477 8.4477 12 9 12L15 12C15.5523 12 16 12.4477 16 13L16 14M12 12L12 18M10 18L14 18");
}

</style>
