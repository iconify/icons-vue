<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y-gq5jb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-center-vertical-32-regular" /></template>
<style>
.y-gq5jb-c {
  fill: currentColor;
  d: path("M16 30a1 1 0 0 1-1-1v-2h-3.5A3.5 3.5 0 0 1 8 23.5v-3a3.5 3.5 0 0 1 3.5-3.5H15v-2H8.5A3.5 3.5 0 0 1 5 11.5v-3A3.5 3.5 0 0 1 8.5 5H15V3a1 1 0 1 1 2 0v2h6.5A3.5 3.5 0 0 1 27 8.5v3a3.5 3.5 0 0 1-3.5 3.5H17v2h3.5a3.5 3.5 0 0 1 3.5 3.5v3a3.5 3.5 0 0 1-3.5 3.5H17v2a1 1 0 0 1-1 1m4.5-5a1.5 1.5 0 0 0 1.5-1.5v-3a1.5 1.5 0 0 0-1.5-1.5h-9a1.5 1.5 0 0 0-1.5 1.5v3a1.5 1.5 0 0 0 1.5 1.5zM25 11.5v-3A1.5 1.5 0 0 0 23.5 7h-15A1.5 1.5 0 0 0 7 8.5v3A1.5 1.5 0 0 0 8.5 13h15a1.5 1.5 0 0 0 1.5-1.5");
}

</style>
