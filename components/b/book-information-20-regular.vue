<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xv7jf8diq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-information-20-regular" /></template>
<style>
.xv7jf8diq {
  fill: currentColor;
  d: path("M4 4v12a2 2 0 0 0 2 2h9.5a.5.5 0 0 0 0-1H6a1 1 0 0 1-1-1h10a1 1 0 0 0 1-1V4a2 2 0 0 0-2-2H6a2 2 0 0 0-2 2m10-1a1 1 0 0 1 1 1v11H5V4a1 1 0 0 1 1-1zm-3.25 2.75a.75.75 0 1 0-1.5 0a.75.75 0 0 0 1.5 0m-.25 6.75a.5.5 0 0 1-1 0v-4a.5.5 0 0 1 1 0z");
}

</style>
