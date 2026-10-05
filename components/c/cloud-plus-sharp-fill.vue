<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfen0bblp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-plus-sharp-fill" /></template>
<style>
.sfen0bblp {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14L12 15L12 21L12 22M8 18L9 18L15 18L16 18M5.7508 17.0673L5 16.874C3.2748 16.4299 2 14.8638 2 13C2 10.7909 3.7909 9 6 9C6 5.6863 8.6863 3 12 3C15.3137 3 18 5.6863 18 9C20.2091 9 22 10.7909 22 13C22 14.8638 20.7252 16.4299 19 16.874L18.2492 17.0673");
}

</style>
