<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljyq-oblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chat-bubble-heart-pair" /></template>
<style>
.ljyq-oblv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 6.25q0 3.928 5.868 7.396q.087.051.184.077t.198.027t.198-.027q.097-.026.184-.077q5.868-3.468 5.868-7.396q0-3.75-3.5-3.75q-1.711 0-2.75 1.159Q7.461 2.5 5.75 2.5q-3.5 0-3.5 3.75M14 13h4.5q1.346 0 2.298.952t.952 2.298V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.227 0-.416-.126l-2.811-1.874H14q-3.25 0-3.25-3.25v-.25Q10.75 13 14 13");
}

</style>
