<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nqq8kl4mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-text-32-regular" /></template>
<style>
.nqq8kl4mz {
  fill: currentColor;
  d: path("M6.5 3A4.5 4.5 0 0 0 2 7.5v12A4.5 4.5 0 0 0 6.5 24H8v4.081c0 1.706 2 2.629 3.298 1.522L17.868 24H25.5a4.5 4.5 0 0 0 4.5-4.5v-12A4.5 4.5 0 0 0 25.5 3zM4 7.5A2.5 2.5 0 0 1 6.5 5h19A2.5 2.5 0 0 1 28 7.5v12a2.5 2.5 0 0 1-2.5 2.5h-8a1 1 0 0 0-.649.24L10 28.08V23a1 1 0 0 0-1-1H6.5A2.5 2.5 0 0 1 4 19.5zM15 15h9a1 1 0 1 0 0-2h-9a1 1 0 1 0 0 2m-4-2H8a1 1 0 1 0 0 2h3a1 1 0 1 0 0-2m-3 4a1 1 0 1 0 0 2h9a1 1 0 1 0 0-2zm13 2a1 1 0 1 1 0-2h3a1 1 0 1 1 0 2z");
}

</style>
