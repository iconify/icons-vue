<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7d7utboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmarks" /></template>
<style>
.t7d7utboq {
  fill: currentColor;
  d: path("M4 22V8q0-.825.588-1.412T6 6h8q.825 0 1.413.588T16 8v14l-6-3zm14-4V4H7V2h11q.825 0 1.413.588T20 4v14z");
}

</style>
