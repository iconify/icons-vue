<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gh9mo5okn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-search-32-filled" /></template>
<style>
.gh9mo5okn {
  fill: currentColor;
  d: path("M17 9V2H8a3 3 0 0 0-3 3v10.124A7.5 7.5 0 0 1 15.5 22c0 1.116-.25 2.223-.735 3.228l2.503 2.504A2.5 2.5 0 0 1 17.95 30H24a3 3 0 0 0 3-3V12h-7a3 3 0 0 1-3-3m2 0V2.117a3 3 0 0 1 1.293.762l5.828 5.828A3 3 0 0 1 26.883 10H20a1 1 0 0 1-1-1M8 28c1.296 0 2.496-.41 3.476-1.11l3.317 3.317a1 1 0 0 0 1.414-1.414l-3.316-3.316A6 6 0 1 0 8 28m0-2a4 4 0 1 1 0-8a4 4 0 0 1 0 8");
}

</style>
