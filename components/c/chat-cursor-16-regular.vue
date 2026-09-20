<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uxtv33xfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-cursor-16-regular" /></template>
<style>
.uxtv33xfr {
  fill: currentColor;
  d: path("M8.01 7.636a.751.751 0 0 1 1.218-.466l5.496 4.498c.545.446.23 1.33-.475 1.33h-2.986a.5.5 0 0 0-.4.2L9.35 15.201c-.435.575-1.35.269-1.35-.451l.002-7q0-.06.008-.114M7 1a6 6 0 0 1 5.74 7.751l-.852-.697q.11-.51.112-1.054a5 5 0 1 0-9.323 2.513a.5.5 0 0 1 .05.383l-.5 1.833l1.673-.557c.15-.033.29-.034.426.053A5 5 0 0 0 7 12l.001-.001v1L7 13a5.97 5.97 0 0 1-2.998-.808l-2.344.783a.5.5 0 0 1-.64-.607l.692-2.543A6 6 0 0 1 1 7a6 6 0 0 1 6-6");
}

</style>
