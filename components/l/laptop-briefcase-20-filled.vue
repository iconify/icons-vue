<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kz8cmjbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-briefcase-20-filled" /></template>
<style>
.kz8cmjbvk {
  fill: currentColor;
  d: path("M15.5 9a1.5 1.5 0 0 1 1.5 1.5v.5h.5a1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5h-6a1.5 1.5 0 0 1-1.5-1.5v-4a1.5 1.5 0 0 1 1.5-1.5h.5v-.5A1.5 1.5 0 0 1 13.5 9zM9 16H2.5a.5.5 0 0 1 0-1H9zm6-11a2 2 0 0 1 2 2v1.502A2.5 2.5 0 0 0 15.5 8h-2a2.5 2.5 0 0 0-2.458 2.042A2.5 2.5 0 0 0 9 12.5V14H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2zm-1.5 5a.5.5 0 0 0-.5.5v.5h3v-.5a.5.5 0 0 0-.5-.5z");
}

</style>
