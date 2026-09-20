<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzyjd_bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airline-seat-legroom-normal-outline" /></template>
<style>
.tzyjd_bae {
  fill: currentColor;
  d: path("M16 21v-7H8q-.825 0-1.412-.587T6 12V3h6v6h5q.825 0 1.413.588T19 11v7h1.5q.65 0 1.075.425T22 19.5t-.425 1.075T20.5 21zm-2-4H5q-.825 0-1.412-.587T3 15V3h2v12h9z");
}

</style>
