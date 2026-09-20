<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xd_u6bcha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:drawer-subtract-20-filled" /></template>
<style>
.xd_u6bcha {
  fill: currentColor;
  d: path("M18 5.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-2 0a.5.5 0 0 0-.5-.5h-4a.5.5 0 0 0 0 1h4a.5.5 0 0 0 .5-.5M6 4h2.207a5.5 5.5 0 0 0-.185 1H6a2 2 0 0 0-2 2h4.207q.149.524.393 1H4v3h3.5a.5.5 0 0 1 .5.5a2 2 0 1 0 4 0a.5.5 0 0 1 .5-.5H16v-.6a5.5 5.5 0 0 0 1-.657V15a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3");
}

</style>
