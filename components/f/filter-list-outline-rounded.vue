<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdpv1humj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-list-outline-rounded" /></template>
<style>
.qdpv1humj {
  fill: currentColor;
  d: path("M11 18q-.425 0-.712-.288T10 17t.288-.712T11 16h2q.425 0 .713.288T14 17t-.288.713T13 18zm-4-5q-.425 0-.712-.288T6 12t.288-.712T7 11h10q.425 0 .713.288T18 12t-.288.713T17 13zM4 8q-.425 0-.712-.288T3 7t.288-.712T4 6h16q.425 0 .713.288T21 7t-.288.713T20 8z");
}

</style>
