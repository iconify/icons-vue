<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqa_97bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmarks-sharp" /></template>
<style>
.rqa_97bdz {
  fill: currentColor;
  d: path("M5 21V6.846h10.289V21l-5.145-2.654zm13-3.558V4H7.789V3H19v14.442z");
}

</style>
