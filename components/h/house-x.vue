<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aho-n3owe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:house-x" /></template>
<style>
.aho-n3owe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 11.8473L10.7072 4.4703C11.0802 4.1543 11.5401 3.9963 12 3.9963M4 10.1528L4 20C4 21.1046 4.8954 22 6 22L18 22C19.1046 22 20 21.1046 20 20L20 12M9 22L9 19C9 17.3431 10.3431 16 12 16C13.6569 16 15 17.3431 15 19L15 22M16 2L22 8M22 2L16 8");
}

</style>
