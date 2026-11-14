<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm9q2bcjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-empty" /></template>
<style>
.hm9q2bcjn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.811 5.205l-3 7q.043-.102.114-.186q.07-.085.162-.145q.092-.061.197-.092q.106-.032.216-.032h19q.11 0 .216.032q.105.031.197.092q.092.06.162.145t.114.186l-3-7q-.043-.102-.114-.186q-.07-.085-.162-.145q-.092-.061-.197-.092q-.106-.032-.216-.032h-13q-.11 0-.216.032q-.105.031-.197.092q-.092.06-.162.145t-.114.186M22.25 12.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146V17q0 2.75 2.75 2.75h15q2.75 0 2.75-2.75z");
}

</style>
