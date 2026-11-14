<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf1wb_0pg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cargo-bike" /></template>
<style>
.wf1wb_0pg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.75 4.75h3.5q2.5 0 2.5 2.5v2.5q0 2.5-2.5 2.5h-3.5q-2.5 0-2.5-2.5v-2.5q0-2.5 2.5-2.5m-5 12.75q0-1.847-.91-2.785l1.469-2.122l1.991 5.176q.041.106.111.196q.071.089.164.153q.094.065.203.098q.108.034.222.034h3.292q.354 3 3.708 3q3.75 0 3.75-3.75T19 13.75q-3.354 0-3.708 3h-2.777L10.2 10.731q-.083-.216-.273-.348q-.061-.042-.129-.071q-.067-.029-.14-.045q-.072-.016-.146-.017q-.073-.001-.146.012t-.142.04q-.068.028-.13.068t-.116.091t-.095.112l-2.34 3.38Q5.873 13.75 5 13.75q-3.75 0-3.75 3.75T5 21.25t3.75-3.75");
}

</style>
