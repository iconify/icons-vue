<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o9buj6mkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-one-page-32-filled" /></template>
<style>
.o9buj6mkp {
  fill: currentColor;
  d: path("M24.75 2A3.25 3.25 0 0 1 28 5.25v21.5A3.25 3.25 0 0 1 24.75 30H7.25A3.25 3.25 0 0 1 4 26.75V5.25A3.25 3.25 0 0 1 7.25 2zM10 22a1 1 0 1 0 0 2h12a1 1 0 1 0 0-2zm0-7a1 1 0 1 0 0 2h12a1 1 0 1 0 0-2zm0-7a1 1 0 0 0 0 2h12a1 1 0 1 0 0-2z");
}

</style>
