<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq3s-gbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:blocks" /></template>
<style>
.tq3s-gbzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7C3 5.8954 3.8954 5 5 5L9 5C10.1046 5 11 5.8954 11 7L11 13L17 13C18.1046 13 19 13.8954 19 15L19 19C19 20.1046 18.1046 21 17 21L5 21C3.8954 21 3 20.1046 3 19L3 7ZM3 13L11 13M11 13L11 21M15 5C15 3.8954 15.8954 3 17 3L19 3C20.1046 3 21 3.8954 21 5L21 7C21 8.1046 20.1046 9 19 9L17 9C15.8954 9 15 8.1046 15 7L15 5Z");
}

</style>
