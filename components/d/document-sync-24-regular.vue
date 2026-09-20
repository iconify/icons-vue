<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ocg6szbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-sync-24-regular" /></template>
<style>
.ocg6szbgg {
  fill: currentColor;
  d: path("M18.5 20a.5.5 0 0 1-.5.5h-5.732A6.5 6.5 0 0 1 11.19 22H18a2 2 0 0 0 2-2V9.828a2 2 0 0 0-.586-1.414l-5.829-5.828A2.05 2.05 0 0 0 12.172 2H6a2 2 0 0 0-2 2v7.498a6.5 6.5 0 0 1 1.5-.422V4a.5.5 0 0 1 .5-.5h6V8a2 2 0 0 0 2 2h4.5zm-5-15.379L17.378 8.5H14a.5.5 0 0 1-.5-.5zM1 17.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 0 0-11 0M9.5 14a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1 0-1h1a2.5 2.5 0 0 0-2-1c-.833 0-1.572.407-2.027 1.036a.5.5 0 1 1-.81-.586A3.5 3.5 0 0 1 6.5 14c.98 0 1.865.403 2.5 1.05v-.55a.5.5 0 0 1 .5-.5M4 19.95v.55a.5.5 0 0 1-1 0v-2a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 0 1h-1c.456.608 1.183 1 2 1c.766 0 1.452-.344 1.911-.888a.5.5 0 0 1 .764.645A3.5 3.5 0 0 1 6.5 21A3.5 3.5 0 0 1 4 19.95");
}

</style>
