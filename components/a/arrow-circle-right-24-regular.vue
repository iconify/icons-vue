<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwzh1sb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-right-24-regular" /></template>
<style>
.hwzh1sb_j {
  fill: currentColor;
  d: path("M12.001 2c5.523 0 10 4.477 10 10s-4.477 10-10 10s-10-4.477-10-10s4.477-10 10-10m0 1.5a8.5 8.5 0 1 0 0 17a8.5 8.5 0 0 0 0-17m-.353 4.053l.073-.084a.75.75 0 0 1 .976-.073l.084.073l4.001 4a.75.75 0 0 1 .073.977l-.073.085l-4.001 4a.75.75 0 0 1-1.134-.977l.073-.084l2.722-2.721H7.75a.75.75 0 0 1-.743-.648L7 12a.75.75 0 0 1 .649-.743l.101-.007h6.69l-2.72-2.72a.75.75 0 0 1-.072-.976l.073-.084z");
}

</style>
