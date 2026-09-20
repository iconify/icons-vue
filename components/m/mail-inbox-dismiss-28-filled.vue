<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="dtjtp-b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-inbox-dismiss-28-filled" /></template>
<style>
.dtjtp-b6s {
  fill: currentColor;
  d: path("M26 7.5a6.5 6.5 0 1 1-13 0a6.5 6.5 0 0 1 13 0m-9.146-3.354a.5.5 0 0 0-.708.708L18.793 7.5l-2.647 2.646a.5.5 0 0 0 .708.708L19.5 8.207l2.646 2.647a.5.5 0 0 0 .708-.708L20.207 7.5l2.647-2.646a.5.5 0 0 0-.708-.708L19.5 6.793zM25 22.75V12.6a7.5 7.5 0 0 1-1.5 1.245V16h-6l-.102.007a.75.75 0 0 0-.648.743a2.75 2.75 0 1 1-5.5 0l-.007-.102A.75.75 0 0 0 10.5 16h-6V7.25c0-.966.784-1.75 1.75-1.75h6.02a7.5 7.5 0 0 1 .595-1.5H6.25A3.25 3.25 0 0 0 3 7.25v15.5A3.25 3.25 0 0 0 6.25 26h15.5A3.25 3.25 0 0 0 25 22.75");
}

</style>
