<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xyhpgn7cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:approvals-app-20-filled" /></template>
<style>
.xyhpgn7cj {
  fill: currentColor;
  d: path("M9.78.72a.75.75 0 0 0-1.06 1.06L9.94 3H9.5a7.5 7.5 0 1 0 7.5 7.5a.75.75 0 0 0-1.5 0a6 6 0 1 1-6.061-6l-.72.72A.75.75 0 0 0 9.78 6.28l2.25-2.25a.75.75 0 0 0 0-1.06zm3.74 6.24a.75.75 0 0 1 .02 1.06l-3.85 4a.75.75 0 0 1-1.08 0l-1.65-1.714a.75.75 0 1 1 1.08-1.04l1.11 1.152l3.31-3.438a.75.75 0 0 1 1.06-.02");
}

</style>
