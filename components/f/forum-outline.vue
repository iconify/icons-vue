<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1vrvwnzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:forum-outline" /></template>
<style>
.g1vrvwnzq {
  fill: currentColor;
  d: path("m22 22l-4-4H8q-.825 0-1.412-.587T6 16v-1h11q.825 0 1.413-.587T19 13V6h1q.825 0 1.413.588T22 8zM4 12.175L5.175 11H15V4H4zM2 17V4q0-.825.588-1.412T4 2h11q.825 0 1.413.588T17 4v7q0 .825-.587 1.413T15 13H6zm2-6V4z");
}

</style>
