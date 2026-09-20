<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kg6jifhyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-bar-vertical-arrow-down-16-filled" /></template>
<style>
.kg6jifhyt {
  fill: currentColor;
  d: path("M10.5 1A1.5 1.5 0 0 1 12 2.5v3.522A5.5 5.5 0 0 0 9 6.6V2.5A1.5 1.5 0 0 1 10.5 1M6 11.5c0-1.708.779-3.234 2-4.243V5.5a1.5 1.5 0 1 0-3 0v6a1.5 1.5 0 0 0 1.199 1.47A5.5 5.5 0 0 1 6 11.5M2.5 7A1.5 1.5 0 0 1 4 8.5v3a1.5 1.5 0 0 1-3 0v-3A1.5 1.5 0 0 1 2.5 7M16 11.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4.854 2.353l.003.003a.5.5 0 0 0 .348.144h.006a.5.5 0 0 0 .35-.146l2-2a.5.5 0 0 0-.707-.708L12 12.293V9.5a.5.5 0 0 0-1 0v2.793l-1.146-1.147a.5.5 0 0 0-.708.708z");
}

</style>
