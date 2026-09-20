<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh5r6jyjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:laptop-chromebook-outline-rounded" /></template>
<style>
.vh5r6jyjf {
  fill: currentColor;
  d: path("M1.5 18.308q-.213 0-.356-.144T1 17.807t.144-.356t.356-.143H3V6.154q0-.666.475-1.141t1.14-.475h14.77q.666 0 1.14.475T21 6.153v11.155h1.5q.213 0 .356.144q.144.143.144.356t-.144.357t-.356.143zm8.885-1h3.23q.154 0 .27-.116q.115-.115.115-.269t-.115-.27t-.27-.114h-3.23q-.154 0-.27.111q-.115.112-.115.273t.116.273t.269.112M4 15.538h16V6.154q0-.27-.173-.442q-.173-.173-.442-.173H4.615q-.269 0-.442.173T4 6.154zm8-5");
}

</style>
