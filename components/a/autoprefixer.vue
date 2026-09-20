<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":193};
const content = `<path class="fn5immbyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:autoprefixer" /></template>
<style>
.fn5immbyj {
  fill: var(--svg-color--dd3835, #dd3835);
  d: path("M62.26 192.232h30.902l9.543-32.72h47.717l9.544 32.72h32.72L128.154 0zm65.894-108.613l16.36 52.716h-32.72zm127.7 70.893l-3.18-13.179l-67.26-6.816l8.635 23.177zM70.44 136.335L3.181 143.15L0 156.331l62.26 3.18z");
}

</style>
