<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gv5l1ubce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:app-folder-32-filled" /></template>
<style>
.gv5l1ubce {
  fill: currentColor;
  d: path("M9.5 7A2.5 2.5 0 0 0 7 9.5v3A2.5 2.5 0 0 0 9.5 15h3a2.5 2.5 0 0 0 2.5-2.5v-3A2.5 2.5 0 0 0 12.5 7zm0 10A2.5 2.5 0 0 0 7 19.5v3A2.5 2.5 0 0 0 9.5 25h3a2.5 2.5 0 0 0 2.5-2.5v-3a2.5 2.5 0 0 0-2.5-2.5zm10-10A2.5 2.5 0 0 0 17 9.5v3a2.5 2.5 0 0 0 2.5 2.5h3a2.5 2.5 0 0 0 2.5-2.5v-3A2.5 2.5 0 0 0 22.5 7zm0 10a2.5 2.5 0 0 0-2.5 2.5v3a2.5 2.5 0 0 0 2.5 2.5h3a2.5 2.5 0 0 0 2.5-2.5v-3a2.5 2.5 0 0 0-2.5-2.5zM3 7.5A4.5 4.5 0 0 1 7.5 3h17A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5zM7.5 5A2.5 2.5 0 0 0 5 7.5v17A2.5 2.5 0 0 0 7.5 27h17a2.5 2.5 0 0 0 2.5-2.5v-17A2.5 2.5 0 0 0 24.5 5z");
}

</style>
