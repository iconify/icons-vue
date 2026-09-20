<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h3fb4mbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:column-triple-edit-20-regular" /></template>
<style>
.h3fb4mbrw {
  fill: currentColor;
  d: path("M1 15a2 2 0 0 0 2 2h1a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2H3a2 2 0 0 0-2 2zm2 1a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1zm4-1a2 2 0 0 0 2 2h.22l.212-.845A3 3 0 0 1 9.475 16H9a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1v8.943l1-1V5a2 2 0 0 0-2-2H9a2 2 0 0 0-2 2zm11-5.866V5a2 2 0 0 0-2-2h-1a2 2 0 0 0-2 2v6.943l1-1V5a1 1 0 0 1 1-1h1a1 1 0 0 1 1 1v4.003a2.9 2.9 0 0 1 1 .13m-7.02 6.243l4.83-4.83a1.87 1.87 0 1 1 2.644 2.646l-4.83 4.829a2.2 2.2 0 0 1-1.02.578l-1.498.374a.89.89 0 0 1-1.079-1.078l.375-1.498a2.2 2.2 0 0 1 .578-1.02");
}

</style>
