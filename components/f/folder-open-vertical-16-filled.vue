<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nf3sqabak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-open-vertical-16-filled" /></template>
<style>
.nf3sqabak {
  fill: currentColor;
  d: path("M11.5 1H6.533l1.717.991A3.5 3.5 0 0 1 10 5.022v7.928a2.5 2.5 0 0 0 2-2.45V7.207l1.56-1.56A1.5 1.5 0 0 0 14 4.585V3.5A2.5 2.5 0 0 0 11.5 1M9 5.022v7.973c0 1.54-1.667 2.502-3 1.732l-2.745-1.585a2.5 2.5 0 0 1-1.25-2.165V3.004c0-1.54 1.667-2.502 3-1.732L7.75 2.857A2.5 2.5 0 0 1 9 5.022");
}

</style>
