<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l4lsrbbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-header-footer-16-filled" /></template>
<style>
.l4lsrbbaf {
  fill: currentColor;
  d: path("M3 2.75C3 1.784 3.784 1 4.75 1h6.5c.966 0 1.75.784 1.75 1.75v10.5A1.75 1.75 0 0 1 11.25 15h-6.5A1.75 1.75 0 0 1 3 13.25zM6 3a1 1 0 0 0 0 2h4a1 1 0 1 0 0-2zm0 8a1 1 0 1 0 0 2h4a1 1 0 1 0 0-2z");
}

</style>
