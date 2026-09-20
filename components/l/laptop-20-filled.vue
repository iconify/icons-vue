<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o-t_2gbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-20-filled" /></template>
<style>
.o-t_2gbvx {
  fill: currentColor;
  d: path("M17.5 15a.5.5 0 0 1 0 1h-15a.5.5 0 0 1 0-1zM15 5a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2z");
}

</style>
