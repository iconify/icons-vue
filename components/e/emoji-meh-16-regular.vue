<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nuopzfogy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:emoji-meh-16-regular" /></template>
<style>
.nuopzfogy {
  fill: currentColor;
  d: path("M7 7a.75.75 0 1 1-1.5 0A.75.75 0 0 1 7 7m2.75.75a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5M6 9a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1zm2-7a6 6 0 1 1 0 12A6 6 0 0 1 8 2m0 1a5 5 0 1 0 0 10A5 5 0 0 0 8 3");
}

</style>
