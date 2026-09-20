<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns4870u1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-briefcase-24-filled" /></template>
<style>
.ns4870u1n {
  fill: currentColor;
  d: path("M12 2v6a2 2 0 0 0 2 2h6v10a2 2 0 0 1-2 2h-5.05q.05-.243.05-.5v-5a2.5 2.5 0 0 0-2-2.45v-.3A2.75 2.75 0 0 0 8.25 11h-3.5q-.392.001-.75.104V4a2 2 0 0 1 2-2zm1.5.5V8a.5.5 0 0 0 .5.5h5.5zM3 15h-.5A1.5 1.5 0 0 0 1 16.5v5A1.5 1.5 0 0 0 2.5 23h8a1.5 1.5 0 0 0 1.5-1.5v-5a1.5 1.5 0 0 0-1.5-1.5H10v-1.25A1.75 1.75 0 0 0 8.25 12h-3.5A1.75 1.75 0 0 0 3 13.75zm1.5-1.25a.25.25 0 0 1 .25-.25h3.5a.25.25 0 0 1 .25.25V15h-4z");
}

</style>
