<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="scaeedcst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flash-12-filled" /></template>
<style>
.scaeedcst {
  fill: currentColor;
  d: path("M8 1a.5.5 0 0 1 .475.658L7.695 4H9.5a.501.501 0 0 1 .384.82L5.09 10.574a1.184 1.184 0 0 1-2.04-1.111L3.82 7H2.5a.5.5 0 0 1-.478-.644l1.5-5l.029-.076a.5.5 0 0 1 .45-.28z");
}

</style>
