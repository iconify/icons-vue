<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ympdhibez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:camping-rounded" /></template>
<style>
.ympdhibez {
  fill: currentColor;
  d: path("M3 20.692v-2.5q0-.267.08-.51t.243-.459l8.062-10.846l-.823-1.108q-.068-.078-.089-.18q-.021-.1-.006-.192q.016-.091.067-.18q.052-.088.131-.155q.177-.135.366-.104t.323.207l.646.883l.646-.883q.135-.176.333-.207t.375.104t.208.332t-.104.375l-.823 1.108l8.042 10.846q.162.218.242.46t.081.51v2.5q0 .347-.23.577t-.578.23H3.808q-.349 0-.578-.23T3 20.692m4.879-.192h8.242L12 14.725z");
}

</style>
