<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="c-ru0abzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-32-regular" /></template>
<style>
.c-ru0abzp {
  fill: currentColor;
  d: path("M7 5.25v21.5c0 .69.56 1.25 1.25 1.25h15.5c.69 0 1.25-.56 1.25-1.25V13h-5.75A3.25 3.25 0 0 1 16 9.75V4H8.25C7.56 4 7 4.56 7 5.25M24.586 11L18 4.414V9.75c0 .69.56 1.25 1.25 1.25zM27 26.75A3.25 3.25 0 0 1 23.75 30H8.25A3.25 3.25 0 0 1 5 26.75V5.25A3.25 3.25 0 0 1 8.25 2h8.818a3.25 3.25 0 0 1 2.298.952l6.682 6.682c.61.61.952 1.436.952 2.298z");
}

</style>
