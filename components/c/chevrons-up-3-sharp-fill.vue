<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9dyq8brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevrons-up-3-sharp-fill" /></template>
<style>
.g9dyq8brn {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.7071 21.2929L12 16L17.2929 21.2929M6.7071 14.7929L12 9.5L17.2929 14.7929M6.7071 8.2929L12 3L17.2929 8.2929");
}

</style>
