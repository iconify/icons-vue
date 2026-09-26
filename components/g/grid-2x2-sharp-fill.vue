<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r629fq0ky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x2-sharp-fill" /></template>
<style>
.r629fq0ky {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2L21 2C21.5523 2 22 2.4477 22 3ZM11 11L4 11L4 13L11 13L11 20L13 20L13 13L20 13L20 11L13 11L13 4L11 4Z");
}

</style>
