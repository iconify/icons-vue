<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6soofapf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:1k" /></template>
<style>
.p6soofapf {
  fill: currentColor;
  d: path("M12 15h1.5v-2.25L15.25 15H17l-2.25-3L17 9h-1.75l-1.75 2.25V9H12zm-3.5 0H10V9H7v1.5h1.5zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
