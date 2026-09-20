<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="w2_24l_2y"/><path class="oa-lg68ww"/><path class="s0g_34bml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:attach-arrow-left-20-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oa-lg68ww {
  d: path("M8.109 15.559l.893-.894a5.48 5.48 0 0 0 .349 1.773l-.182.181A2.75 2.75 0 0 1 5.28 12.73l5.657-5.657a.75.75 0 1 1 1.06 1.06l-5.656 5.658a1.25 1.25 0 0 0 1.768 1.768z");
  fill: currentColor;
}

.s0g_34bml {
  d: path("M19 14.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0zm-2.147.354l.003-.003a.499.499 0 0 0 .144-.348v-.006a.5.5 0 0 0-.146-.35l-2-2a.5.5 0 0 0-.708.707L15.293 14H12.5a.5.5 0 0 0 0 1h2.793l-1.147 1.146a.5.5 0 0 0 .708.708l2-2z");
  fill: currentColor;
}

.w2_24l_2y {
  d: path("M5.28 10.609l5.304-5.304a2.75 2.75 0 0 1 4.064 3.697a5.487 5.487 0 0 1 1.611.285a4.252 4.252 0 0 0-6.736-5.042L4.22 9.548a.75.75 0 0 0 1.06 1.06z");
  fill: currentColor;
}

</style>
