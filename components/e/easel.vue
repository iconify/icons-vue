<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad1eawq9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:easel" /></template>
<style>
.ad1eawq9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 3L18 3C19.1046 3 20 3.8954 20 5L20 16L4 16L4 5C4 3.8954 4.8954 3 6 3ZM2 16L22 16M8 16L6.5 21M16 16L17.5 21M12 16L12 19");
}

</style>
