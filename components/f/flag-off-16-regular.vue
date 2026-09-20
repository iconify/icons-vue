<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e3o6m3lwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-off-16-regular" /></template>
<style>
.e3o6m3lwz {
  fill: currentColor;
  d: path("m9.293 10l4.853 4.854a.5.5 0 0 0 .708-.708l-13-13a.5.5 0 1 0-.708.708L3 3.707V13.5a.5.5 0 0 0 1 0V10zm-1-1H4V4.707zm3.735 0h-.907l1 1H13a.5.5 0 0 0 .407-.79L11.114 6l2.293-3.21A.5.5 0 0 0 13 2H4.121l1 1h6.907l-1.935 2.71a.5.5 0 0 0 0 .58z");
}

</style>
