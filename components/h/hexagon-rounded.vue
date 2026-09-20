<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzn3-m9vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hexagon-rounded" /></template>
<style>
.xzn3-m9vw {
  fill: currentColor;
  d: path("M8.027 20.5q-.435 0-.808-.215q-.373-.214-.59-.593l-3.992-6.884q-.218-.38-.218-.808t.217-.808L6.63 4.308q.217-.38.59-.594t.808-.214h7.946q.435 0 .808.214q.373.215.59.594l3.993 6.884q.217.38.217.808t-.217.808l-3.993 6.884q-.217.38-.59.594t-.808.214z");
}

</style>
