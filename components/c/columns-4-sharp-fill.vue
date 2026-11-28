<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="folyyvbmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:columns-4-sharp-fill" /></template>
<style>
.folyyvbmu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM6.5 4L6.5 20L8.5 20L8.5 4L6.5 4ZM11 4L11 20L13 20L13 4L11 4ZM15.5 4L15.5 20L17.5 20L17.5 4L15.5 4Z");
}

</style>
