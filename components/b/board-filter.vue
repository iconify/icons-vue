<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcczp92jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:board-filter" /></template>
<style>
.mcczp92jc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 2.25Q7.5 2.25 7.5 5v13q0 2.75-2.75 2.75T2 18V5q0-1.139.805-1.945q.806-.805 1.945-.805M14.25 5q0-2.75-2.75-2.75T8.75 5v6q0 2.75 2.75 2.75T14.25 11zm4-2.75Q21 2.25 21 5v3q0 2.75-2.75 2.75T15.5 8V5q0-2.75 2.75-2.75m-1.547 12h2.594q1.058.001 1.507.958q.449.958-.227 1.772l-.903 1.083q-.174.209-.174.48v1.868q.001.707-.601 1.079q-.602.373-1.235.056q-1.164-.583-1.164-1.885v-1.118q0-.271-.174-.48l-.902-1.083q-.677-.814-.228-1.772q.449-.957 1.507-.958m0 1.5q-.104 0-.149.095q-.044.095.022.175l.902 1.083q.522.625.522 1.44q0-.815.522-1.44l.901-1.083q.067-.08.023-.175t-.149-.095z");
}

</style>
