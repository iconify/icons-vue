<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o36u89b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-open-outline" /></template>
<style>
.o36u89b9o {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h6l2 2h8q.825 0 1.413.588T22 8H11.175l-2-2H4v12l2.4-8h17.1l-2.575 8.575q-.2.65-.737 1.038T19 20zm2.1-2H19l1.8-6H7.9zm0 0l1.8-6zM4 8V6z");
}

</style>
