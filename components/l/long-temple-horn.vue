<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpzkbcbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:long-temple-horn" /></template>
<style>
.rpzkbcbbs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.258 12.394q-.536 3.748-3.425 5.913Q3.75 18.869 3.75 20q0 2.25 8.25 2.25q3.181 0 5.45-.454q2.799-.56 2.8-1.795v-.002q-.001-1.03-1.945-1.59q-3.014-2.176-3.561-6.002l-.98-7.843l.704-2.348Q14.5 2.11 14.5 2q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043q-.072-.014-.146-.014h-3.5q-.11 0-.216.032q-.142.042-.258.137q-.116.094-.186.225q-.071.132-.086.28t.028.292l.704 2.348zm3.998.199q.449 3.144 2.305 5.328q-1.609-.171-3.561-.171q-2.008 0-3.527.133q1.825-2.169 2.269-5.277l1.002-8.013q.02-.157-.026-.309l-.46-1.534h1.484l-.46 1.534q-.046.152-.026.309z");
}

</style>
