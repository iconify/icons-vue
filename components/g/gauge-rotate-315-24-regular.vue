<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpuk5-v3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-315-24-regular" /></template>
<style>
.lpuk5-v3f {
  fill: currentColor;
  d: path("M12.81 2.032C17.954 2.444 22 6.75 22 12c0 5.522-4.477 10-10 10S2 17.522 2 12a9.98 9.98 0 0 1 3.166-7.301a.751.751 0 0 1 1.025 1.094a8.5 8.5 0 1 0 6.498-2.266a.75.75 0 0 1 .12-1.495M6.887 7.86c-.259-.603.371-1.233.974-.975l.13.07c1.637 1.084 3.285 2.154 4.884 3.293c.404.288.745.543.89.688a2 2 0 0 1-2.828 2.828c-.145-.145-.4-.486-.688-.89c-.903-1.267-2.427-3.568-3.293-4.884z");
}

</style>
