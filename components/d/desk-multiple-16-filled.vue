<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ztlu44bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-multiple-16-filled" /></template>
<style>
.ztlu44bfb {
  fill: currentColor;
  d: path("M7 11.25A1.75 1.75 0 0 1 5.25 13h-2.5A1.75 1.75 0 0 1 1 11.25V7h6zM11.25 4c.966 0 1.75.784 1.75 1.75v6.75a.5.5 0 0 1-1 0V6H1v-.25C1 4.784 1.784 4 2.75 4zm.001-2a3.75 3.75 0 0 1 3.75 3.75v4.75a.5.5 0 0 1-1 0V5.75A2.75 2.75 0 0 0 11.251 3h-8.08c.282-.59.882-1 1.58-1zM3 8.5a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1z");
}

</style>
