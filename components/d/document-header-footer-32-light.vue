<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ra5gjobjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-header-footer-32-light" /></template>
<style>
.ra5gjobjq {
  fill: currentColor;
  d: path("M24.75 2A3.25 3.25 0 0 1 28 5.25v21.5A3.25 3.25 0 0 1 24.75 30H7.25a3.25 3.25 0 0 1-3.246-3.083L4 26.75V5.25A3.25 3.25 0 0 1 7.25 2zM7.25 3A2.25 2.25 0 0 0 5 5.25v21.5l.012.23A2.25 2.25 0 0 0 7.25 29h17.5A2.25 2.25 0 0 0 27 26.75V5.25A2.25 2.25 0 0 0 24.75 3zM21.5 21a2 2 0 1 1 0 4h-11a2 2 0 1 1 0-4zm0-14a2 2 0 1 1 0 4h-11a2 2 0 1 1 0-4z");
}

</style>
