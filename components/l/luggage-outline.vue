<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xctdv-b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:luggage-outline" /></template>
<style>
.xctdv-b6m {
  fill: currentColor;
  d: path("M7.462 20q-.671 0-1.144-.472t-.472-1.144V8q0-.671.472-1.143q.473-.473 1.144-.473h2.154V4.616q0-.67.472-1.143T11.23 3h1.538q.671 0 1.143.472t.472 1.144v1.769h2.154q.671 0 1.144.472T18.154 8v10.385q0 .67-.472 1.143q-.472.472-1.143.472v.23q0 .31-.23.54t-.54.23t-.54-.23t-.229-.54V20H9v.23q0 .31-.23.54t-.54.23t-.539-.23t-.23-.54zm0-1h9.077q.269 0 .442-.173t.173-.442V8q0-.27-.173-.442q-.173-.173-.443-.173H7.462q-.27 0-.443.173T6.846 8v10.385q0 .269.173.442t.443.173m2.154-1.77h1V9.155h-1zm3.769 0h1V9.155h-1zm-2.77-10.846h2.77V4.615q0-.269-.173-.442T12.769 4h-1.538q-.27 0-.442.173q-.173.173-.173.442zM12 13.192");
}

</style>
