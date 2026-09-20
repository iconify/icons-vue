<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdavhzbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmarks-sharp" /></template>
<style>
.sdavhzbyv {
  fill: currentColor;
  d: path("M4 22V6h12v16l-6-3zm14-4V4H7V2h13v16z");
}

</style>
