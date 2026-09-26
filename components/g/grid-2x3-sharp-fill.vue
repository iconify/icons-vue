<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ibn--6bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-2x3-sharp-fill" /></template>
<style>
.ibn--6bup {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2L21 2C21.5523 2 22 2.4477 22 3ZM11 8L4 8L4 10L11 10L11 14L4 14L4 16L11 16L11 20L13 20L13 16L20 16L20 14L13 14L13 10L20 10L20 8L13 8L13 4L11 4Z");
}

</style>
