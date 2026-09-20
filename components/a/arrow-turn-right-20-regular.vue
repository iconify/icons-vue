<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y5lz3bcni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-right-20-regular" /></template>
<style>
.y5lz3bcni {
  fill: currentColor;
  d: path("M11.146 3.146a.5.5 0 0 1 .708 0l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708L14.293 8H8a2 2 0 0 0-2 2v6.5a.5.5 0 0 1-1 0V10a3 3 0 0 1 3-3h6.293l-3.147-3.146a.5.5 0 0 1 0-.708");
}

</style>
