<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2pmutb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-text-wrap" /></template>
<style>
.b2pmutb1a {
  fill: currentColor;
  d: path("M4 20V4h2v16zm14 0V4h2v16zm-7.4-2.45L7.05 14l3.55-3.525l1.4 1.4L10.875 13H13q.825 0 1.413-.587T15 11t-.587-1.412T13 9H7V7h6q1.65 0 2.825 1.175T17 11t-1.175 2.825T13 15h-2.125L12 16.125z");
}

</style>
