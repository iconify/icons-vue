<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l4jpqqbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-open-down-16-filled" /></template>
<style>
.l4jpqqbxy {
  fill: currentColor;
  d: path("M1 11.495V6.53l.991 1.716a3.5 3.5 0 0 0 3.031 1.75h7.928a2.5 2.5 0 0 1-2.45 2H7.207l-1.56 1.56a1.5 1.5 0 0 1-1.061.44H3.5a2.5 2.5 0 0 1-2.5-2.5m4.022-2.5h7.973c1.54 0 2.502-1.667 1.732-3L13.142 3.25A2.5 2.5 0 0 0 10.978 2H3.004C1.464 2 .502 3.667 1.272 5l1.585 2.745a2.5 2.5 0 0 0 2.165 1.25");
}

</style>
