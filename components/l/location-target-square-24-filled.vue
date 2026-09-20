<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkhn1rbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-target-square-24-filled" /></template>
<style>
.jkhn1rbbu {
  fill: currentColor;
  d: path("M6.25 3A3.25 3.25 0 0 0 3 6.25v11.5A3.25 3.25 0 0 0 6.25 21h11.5A3.25 3.25 0 0 0 21 17.75V6.25A3.25 3.25 0 0 0 17.75 3zM9 12a3 3 0 1 1 6 0a3 3 0 0 1-6 0m-1.438-.75a4.5 4.5 0 0 1 3.688-3.688V6.75a.75.75 0 0 1 1.5 0v.812a4.5 4.5 0 0 1 3.688 3.688h.812a.75.75 0 0 1 0 1.5h-.812a4.5 4.5 0 0 1-3.688 3.688v.812a.75.75 0 0 1-1.5 0v-.812a4.5 4.5 0 0 1-3.688-3.688H6.75a.75.75 0 0 1 0-1.5zM13.5 12a1.5 1.5 0 1 0-3 0a1.5 1.5 0 0 0 3 0");
}

</style>
