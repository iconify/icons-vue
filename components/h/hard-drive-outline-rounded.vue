<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjg29jqyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hard-drive-outline-rounded" /></template>
<style>
.wjg29jqyg {
  fill: currentColor;
  d: path("M4.616 16.423h14.769q.269 0 .442-.173t.173-.442v-5.154H4v5.154q0 .269.173.442t.443.173m13.206-2.178q.294-.293.294-.707t-.294-.706q-.293-.294-.707-.294q-.413 0-.706.294t-.294.706t.294.707t.706.293t.707-.293M21 9.654h-1.402l-2.423-2.5H6.825l-2.423 2.5H3l2.944-3.021q.218-.237.522-.358t.628-.121h9.812q.323 0 .628.121t.522.358zM4.616 17.423q-.672 0-1.144-.472T3 15.808V9.654h18v6.154q0 .67-.472 1.143q-.472.472-1.144.472z");
}

</style>
