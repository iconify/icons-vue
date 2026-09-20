<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugamqzt_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:call-chevron-down-24-filled" /></template>
<style>
.ugamqzt_h {
  fill: currentColor;
  d: path("M6.85 2.095c1.008-.323 2.086.199 2.518 1.217l.86 2.028c.375.883.167 1.922-.514 2.568L7.82 9.706q.175 1.614 1.084 3.178a8.7 8.7 0 0 0 2.272 2.594l2.274-.76c.863-.287 1.802.044 2.331.821l1.233 1.81c.615.904.504 2.15-.26 2.917l-.817.82c-.813.817-1.976 1.114-3.051.778q-3.809-1.188-7.003-7.053q-3.2-5.876-2.26-9.968c.265-1.148 1.083-2.062 2.15-2.404zM20.72 4.72a.75.75 0 0 1 1.06 1.06l-4 4a.75.75 0 0 1-1.06 0l-4-4a.75.75 0 0 1 1.06-1.06l3.47 3.47z");
}

</style>
