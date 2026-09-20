<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sjygs8clv"/><path class="hhc0ntbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-npm" /></template>
<style>
.hhc0ntbct {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.25 7.25h17.5v17.5h-3.5v-14H16v14H7.25");
}

.sjygs8clv {
  fill: var(--svg-color--c12127, #c12127);
  d: path("M2 2h28v28H2");
}

</style>
