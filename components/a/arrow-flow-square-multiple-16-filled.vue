<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t2ymhdcuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-square-multiple-16-filled" /></template>
<style>
.t2ymhdcuc {
  fill: currentColor;
  d: path("M13 4.503c.606.456 1 1.18 1 1.997v3A4.5 4.5 0 0 1 9.5 14h-3c-.817 0-1.54-.394-1.996-1H9.5A3.5 3.5 0 0 0 13 9.5zM9.5 2A2.5 2.5 0 0 1 12 4.5v5A2.5 2.5 0 0 1 9.5 12h-5A2.5 2.5 0 0 1 2 9.5V7.176q.239.072.5.074A1.75 1.75 0 0 0 4.176 6h.074a2 2 0 0 1 1.6.8A3 3 0 0 0 8.25 8h1.043L8.146 9.146a.5.5 0 1 0 .708.708l2-2a.5.5 0 0 0 0-.708l-2-2a.5.5 0 1 0-.708.708L9.293 7H8.25a2 2 0 0 1-1.6-.8A3 3 0 0 0 4.25 5h-.074a1.75 1.75 0 0 0-2.074-1.203A2.5 2.5 0 0 1 4.5 2zm-7 2.75a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
