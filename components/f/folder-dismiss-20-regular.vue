<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="odztzyb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-dismiss-20-regular" /></template>
<style>
.odztzyb9v {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M6.982 3c.464 0 .91.185 1.238.513L9.707 5H15.5A2.5 2.5 0 0 1 18 7.5v2.757a5.5 5.5 0 0 0-1-.656V7.5A1.5 1.5 0 0 0 15.5 6H9.707l-1.56 1.56A1.5 1.5 0 0 1 7.085 8H3v6.5A1.5 1.5 0 0 0 4.5 16h4.708q.149.524.394 1H4.5A2.5 2.5 0 0 1 2 14.5v-9A2.5 2.5 0 0 1 4.5 3zm9.372 9.647a.5.5 0 0 0-.707 0L14.5 13.793l-1.146-1.146a.5.5 0 1 0-.707.707l1.146 1.146l-1.146 1.146a.5.5 0 1 0 .707.707l1.146-1.146l1.146 1.146a.5.5 0 1 0 .707-.707L15.208 14.5l1.146-1.146a.5.5 0 0 0 0-.707M4.5 4A1.5 1.5 0 0 0 3 5.5V7h4.086a.5.5 0 0 0 .353-.146L8.793 5.5l-1.28-1.28a.75.75 0 0 0-.53-.22z");
}

</style>
