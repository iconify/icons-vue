<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r9zwy09dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-3x2-fill" /></template>
<style>
.r9zwy09dw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2C20.2092 2 22 3.7909 22 6L22 18C22 20.2092 20.2092 22 18 22L6 22C3.7909 22 2 20.2092 2 18L2 6C2 3.7909 3.7909 2 6 2L18 2ZM8 11L4 11L4 13L8 13L8 20L10 20L10 13L14 13L14 20L16 20L16 13L20 13L20 11L16 11L16 4L14 4L14 11L10 11L10 4L8 4Z");
}

</style>
