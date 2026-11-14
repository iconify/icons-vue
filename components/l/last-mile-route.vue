<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqztnv0ex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:last-mile-route" /></template>
<style>
.iqztnv0ex {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.554 6.75H11q-.662 0-1.04.591q-.416.652-.338 1.597Q9.815 11.25 12 11.25q3.565 0 3.872 3.688q.121 1.449-.568 2.528q-.82 1.284-2.304 1.284H8.446Q8.098 21 5.5 21q-3 0-3-3t3-3q2.598 0 2.946 2.25H13q.662 0 1.04-.591q.416-.652.338-1.597Q14.185 12.75 12 12.75q-3.565 0-3.872-3.688q-.121-1.449.568-2.528Q9.516 5.25 11 5.25h4.554q.147-.951.696-1.5Q17 3 18.5 3q3 0 3 3t-3 3q-2.598 0-2.946-2.25");
}

</style>
