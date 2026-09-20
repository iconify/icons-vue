<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c2dx-nuju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-header-arrow-down-16-regular" /></template>
<style>
.c2dx-nuju {
  fill: currentColor;
  d: path("M4.75 1A1.75 1.75 0 0 0 3 2.75v10.5c0 .966.784 1.75 1.75 1.75h2.587a5.5 5.5 0 0 1-1.08-1H4.75a.75.75 0 0 1-.75-.75V2.75A.75.75 0 0 1 4.75 2h6.5a.75.75 0 0 1 .75.75v2.457q.524.149 1 .393V2.75A1.75 1.75 0 0 0 11.25 1zM6 3a1 1 0 0 0 0 2h4a1 1 0 1 0 0-2zm9 7.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4.854 2.353l.003.003a.5.5 0 0 0 .348.144h.006a.5.5 0 0 0 .35-.146l2-2a.5.5 0 0 0-.707-.708L11 11.293V8.5a.5.5 0 0 0-1 0v2.793l-1.146-1.147a.5.5 0 0 0-.708.708z");
}

</style>
