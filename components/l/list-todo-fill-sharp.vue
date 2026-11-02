<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqebcwb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-todo-fill-sharp" /></template>
<style>
.qqebcwb7n {
  fill: currentColor;
  d: path("M3 3h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m1 6h4V5H4Zm9-3h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2M3.707 16.293L5 17.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414M13 16h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
