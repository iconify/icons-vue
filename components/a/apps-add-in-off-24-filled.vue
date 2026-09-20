<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wsu6rwbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:apps-add-in-off-24-filled" /></template>
<style>
.wsu6rwbax {
  fill: currentColor;
  d: path("M3.283 4.344L2.22 3.28a.75.75 0 1 1 1.06-1.06l18.5 18.5a.75.75 0 0 1-1.06 1.06l-1.064-1.063A2.5 2.5 0 0 1 18.5 21h-13A2.5 2.5 0 0 1 3 18.5v-13c0-.417.102-.81.283-1.156M17.939 19L13 14.06V19zm-8-8L5 6.06V11zM11 5.5v2.318l2 2V5.5A2.5 2.5 0 0 0 10.5 3H6.182l2 2H10.5a.5.5 0 0 1 .5.5m5.181 7.5l-2-2H18.5a2.5 2.5 0 0 1 2.5 2.5v4.319l-2-2V13.5a.5.5 0 0 0-.5-.5zM11 13H5v5.5a.5.5 0 0 0 .5.5H11zm6.883-10.993L18 2a1 1 0 0 1 .993.883L19 3v2h2a1 1 0 0 1 .993.883L22 6a1 1 0 0 1-.883.993L21 7h-2v2a1 1 0 0 1-.883.993L18 10a1 1 0 0 1-.993-.883L17 9V7h-2a1 1 0 0 1-.993-.883L14 6a1 1 0 0 1 .883-.993L15 5h2V3a1 1 0 0 1 .883-.993");
}

</style>
