<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sf-yb8bcz"/><circle class="ox62ppbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-plagiarism" /></template>
<style>
.ox62ppbtl {
  cx: 11.5px;
  cy: 14.5px;
  r: 1.5px;
  fill: currentColor;
}

.sf-yb8bcz {
  fill: currentColor;
  d: path("M14 2H6c-1.1 0-2 .9-2 2v16c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8zm1.04 17.45l-1.88-1.88c-1.33.71-3.01.53-4.13-.59a3.495 3.495 0 0 1 0-4.95a3.495 3.495 0 0 1 4.95 0a3.48 3.48 0 0 1 .59 4.13l1.88 1.88zM13 9V3.5L18.5 9z");
}

</style>
