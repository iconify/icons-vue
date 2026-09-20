<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b6zf83bex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-dismiss-16-filled" /></template>
<style>
.b6zf83bex {
  fill: currentColor;
  d: path("M11 1H5a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h2.257a5.5 5.5 0 0 1-.657-1H5a1 1 0 0 1-1-1v-.003h2.206A5.5 5.5 0 0 1 13 6.207V3a2 2 0 0 0-2-2M5.75 3h4.5a.75.75 0 0 1 .75.75v.5a.75.75 0 0 1-.75.75h-4.5A.75.75 0 0 1 5 4.25v-.5A.75.75 0 0 1 5.75 3M16 11.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-2.646-1.146a.5.5 0 0 0-.708-.708L11.5 10.793l-1.146-1.147a.5.5 0 0 0-.708.708l1.147 1.146l-1.147 1.146a.5.5 0 0 0 .708.708l1.146-1.147l1.146 1.147a.5.5 0 0 0 .708-.708L12.207 11.5z");
}

</style>
