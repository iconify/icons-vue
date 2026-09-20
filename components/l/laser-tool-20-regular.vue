<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jqn2g7b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laser-tool-20-regular" /></template>
<style>
.jqn2g7b3c {
  fill: currentColor;
  d: path("M4 2.5a.5.5 0 0 0-1 0V5a2 2 0 0 0 1 1.732V7.5A1.5 1.5 0 0 0 5.5 9h4v3.5a.5.5 0 0 0 1 0V9h4A1.5 1.5 0 0 0 16 7.5v-.768A2 2 0 0 0 17 5V2.5a.5.5 0 0 0-1 0V5a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1zM5 7h10v.5a.5.5 0 0 1-.5.5h-9a.5.5 0 0 1-.5-.5zm.5 7a.5.5 0 0 0 0 1H7a.5.5 0 0 0 0-1zm7 .5a.5.5 0 0 1 .5-.5h1.5a.5.5 0 0 1 0 1H13a.5.5 0 0 1-.5-.5M10 15a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m0 1a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0v-2a.5.5 0 0 1 .5-.5m-1.146-.146a.5.5 0 0 0-.708-.708l-1.5 1.5a.5.5 0 0 0 .708.708zm2.292-.708a.5.5 0 0 0 0 .708l1.5 1.5a.5.5 0 0 0 .708-.708l-1.5-1.5a.5.5 0 0 0-.708 0");
}

</style>
