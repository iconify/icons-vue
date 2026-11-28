<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avlm43bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fit-height-sharp" /></template>
<style>
.avlm43bzm {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 2L20 2L20 22L4 22ZM12 6L12 18M8.7071 9.2929L12 6L15.2929 9.2929M8.7071 14.7071L12 18L15.2929 14.7071");
}

</style>
