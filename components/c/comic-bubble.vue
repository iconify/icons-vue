<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o140mmb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:comic-bubble" /></template>
<style>
.o140mmb8w {
  fill: currentColor;
  d: path("M11 20.9L8.1 18H4v-4.1L1.1 11L4 8.1V4h4.1L11 1.1L13.9 4H18v4.1l2.9 2.9l-2.9 2.9l2.875 5.65q.175.325.1.638t-.275.512t-.512.275t-.638-.1L13.9 18z");
}

</style>
