<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y80vh4bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ink-highlighter-off" /></template>
<style>
.y80vh4bkm {
  fill: currentColor;
  d: path("M16.625 13.8L11.2 8.375L16 3.6q.6-.6 1.4-.6t1.4.6l2.6 2.6q.6.6.6 1.4T21.4 9zm3.175 8.8l-6-6l-3.8 3.8q-.6.6-1.4.6t-1.4-.6l-.05-.05l-.65.65h-5l3.15-3.15l-.05-.05q-.6-.6-.6-1.4t.6-1.4l3.8-3.8l-7-7l1.425-1.425l18.4 18.4z");
}

</style>
