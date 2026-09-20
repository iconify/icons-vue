<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r4usymb2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-word-20-regular" /></template>
<style>
.r4usymb2v {
  fill: currentColor;
  d: path("M8 9a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2zm2.586-7a1.5 1.5 0 0 1 1.06.44l3.914 3.914a1.5 1.5 0 0 1 .44 1.06V16a2 2 0 0 1-2 2h-3.769a3 3 0 0 0 .595-1H14a1 1 0 0 0 1-1V8h-3.5A1.5 1.5 0 0 1 10 6.5V3H6a1 1 0 0 0-1 1v4H4V4a2 2 0 0 1 2-2zm-3.163 9.001L6.8 14.3L6.136 11H4.834L4.2 14.3L3.562 11H2.5l1.035 5h1.299l.666-3l.636 3l1.287-.001L8.5 11zM11 6.5a.5.5 0 0 0 .5.5h3.293L11 3.207z");
}

</style>
