<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddkxhlb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:file-map-stack-outline-sharp" /></template>
<style>
.ddkxhlb0d {
  fill: currentColor;
  d: path("M6.5 17V3h14v14zm1-1h12V4h-12zm-4 4V6.616h1V19h12.385v1zm4-16v12zm5.422 5.767q-.23-.233-.23-.578t.234-.574t.578-.23t.574.233t.23.578t-.233.574t-.578.23t-.575-.233m.578 4.272q1.621-1.38 2.426-2.573t.805-2.193q0-1.529-.972-2.42q-.972-.892-2.259-.892t-2.259.892t-.972 2.42q0 1 .805 2.193T13.5 14.04");
}

</style>
