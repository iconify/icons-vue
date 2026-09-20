<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jji9hyblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-off-outline" /></template>
<style>
.jji9hyblu {
  fill: currentColor;
  d: path("M21.775 18.95L20 17.175V8h-9.15l-2-2l-2-2H9.7l2 2H20q.825 0 1.413.588T22 8v10q0 .275-.05.513t-.175.437m-1.3 4.35l-3.3-3.3H4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4l2 2H4v12h11.175L.7 3.5l1.4-1.4l19.8 19.8zm-6.05-11.725");
}

</style>
