<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u-r1ws25t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-sync-complete-16-filled" /></template>
<style>
.u-r1ws25t {
  fill: currentColor;
  d: path("M4.03 5.507a4 4 0 0 1 7.887-.323A5.5 5.5 0 0 0 5.207 12H4.25a3.25 3.25 0 0 1-.22-6.493M15 10.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-2.146-1.854a.5.5 0 0 0-.708 0L9.5 11.293l-.646-.647a.5.5 0 0 0-.708.708l1 1a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0 0-.708");
}

</style>
