<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a48r-z2kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-checkmark-16-regular" /></template>
<style>
.a48r-z2kc {
  fill: currentColor;
  d: path("M6 1a2 2 0 0 0-2 2v2.207a5.5 5.5 0 0 1 1-.185V3a1 1 0 0 1 1-1h3v2.5A1.5 1.5 0 0 0 10.5 6H13v7a1 1 0 0 1-1 1H9.743a5.5 5.5 0 0 1-1.08 1H12a2 2 0 0 0 2-2V5.414a1.5 1.5 0 0 0-.44-1.06l-2.914-2.915A1.5 1.5 0 0 0 9.586 1zm6.793 4H10.5a.5.5 0 0 1-.5-.5V2.207zM10 10.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0M7.854 8.646a.5.5 0 0 0-.708 0L4.5 11.293l-.646-.647a.5.5 0 0 0-.708.708l1 1a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0 0-.708");
}

</style>
