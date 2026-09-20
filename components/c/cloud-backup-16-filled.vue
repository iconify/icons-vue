<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r44s6_2wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-backup-16-filled" /></template>
<style>
.r44s6_2wn {
  fill: currentColor;
  d: path("M4.03 5.507a4 4 0 0 1 7.887-.323A5.5 5.5 0 0 0 5.207 12H4.25a3.25 3.25 0 0 1-.22-6.493M15 10.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4.854-2.353l-2 2a.5.5 0 0 0 .708.707L10 9.707V12.5a.5.5 0 0 0 1 0V9.707l1.146 1.147a.5.5 0 0 0 .708-.708l-2-2A.5.5 0 0 0 10.503 8h-.006a.5.5 0 0 0-.348.144z");
}

</style>
