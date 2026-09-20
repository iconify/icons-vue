<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-lzprq1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-code-outline" /></template>
<style>
.u-lzprq1k {
  fill: currentColor;
  d: path("M4 18V6v13zm0 2q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h6l2 2h8q.825 0 1.413.588T22 8v5h-2V8h-8.825l-2-2H4v12h5v2zm10.6 2.6L11 19l3.6-3.6l1.4 1.425L13.825 19L16 21.175zm4.8 0L18 21.175L20.175 19L18 16.825l1.4-1.425L23 19z");
}

</style>
