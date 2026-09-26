<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5a7rwu8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote" /></template>
<style>
.z5a7rwu8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 17L22 7C22 5.8954 21.1046 5 20 5L4 5C2.8954 5 2 5.8954 2 7L2 17C2 18.1046 2.8954 19 4 19L20 19C21.1046 19 22 18.1046 22 17ZM14 12C14 13.1046 13.1046 14 12 14C10.8954 14 10 13.1046 10 12C10 10.8954 10.8954 10 12 10C13.1046 10 14 10.8954 14 12ZM17 9L18 9M7 15L6 15");
}

</style>
