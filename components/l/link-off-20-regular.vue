<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="prd21jbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-off-20-regular" /></template>
<style>
.prd21jbkl {
  fill: currentColor;
  d: path("M2.146 2.147a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707L13.293 14H12a.5.5 0 0 1-.09-.992L12 13h.293l-2.5-2.5H6a.5.5 0 0 1-.09-.992L6 9.5h2.793L6.293 7H6a3 3 0 0 0-.197 5.993L6 13h2a.5.5 0 0 1 .09.992L8 14H6a4 4 0 0 1-.653-7.946l-3.2-3.2a.5.5 0 0 1 0-.707M14 6a4 4 0 0 1 1.729 7.608l-.768-.768a2.999 2.999 0 0 0-.764-5.833L14 7h-2a.5.5 0 0 1-.09-.992L12 6zm0 3.5a.5.5 0 0 1 .09.992L14 10.5h-1.379l-1-1z");
}

</style>
