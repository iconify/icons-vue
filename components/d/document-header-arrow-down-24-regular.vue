<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0540ob3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-header-arrow-down-24-regular" /></template>
<style>
.i0540ob3k {
  fill: currentColor;
  d: path("M8.505 5.004a1.5 1.5 0 0 0 0 3h7a1.5 1.5 0 0 0 0-3zm11.49-.908A2.25 2.25 0 0 0 17.75 2H6.25l-.154.005A2.25 2.25 0 0 0 4 4.25v15.5l.005.154A2.25 2.25 0 0 0 6.25 22h6.56a6.5 6.5 0 0 1-1.078-1.5H6.25l-.102-.007a.75.75 0 0 1-.648-.743V4.25l.007-.102A.75.75 0 0 1 6.25 3.5h11.5l.102.007a.75.75 0 0 1 .648.743v6.826a6.5 6.5 0 0 1 1.5.422V4.25zM23 17.5a5.5 5.5 0 1 1-11 0a5.5 5.5 0 0 1 11 0m-5-3a.5.5 0 0 0-1 0v4.793l-1.646-1.647a.5.5 0 0 0-.708.708l2.5 2.5a.5.5 0 0 0 .708 0l2.5-2.5a.5.5 0 0 0-.708-.708L18 19.293z");
}

</style>
