<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwa6-x2xc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-l-outline-rounded" /></template>
<style>
.bwa6-x2xc {
  fill: currentColor;
  d: path("M3 17.385V8.269q0-1.356.977-2.322t2.35-.966h11.346q1.373 0 2.35.966T21 8.269v9.116q0 .666-.474 1.14T19.385 19H4.615q-.666 0-1.14-.475T3 17.386M4.616 18h14.769q.269 0 .442-.173t.173-.442V8.269q0-.96-.683-1.624q-.684-.664-1.644-.664H6.327q-.96 0-1.643.664Q4 7.31 4 8.27v9.116q0 .269.173.442t.443.173m0 0H4h16zm7.103-3.717V9.329q0-.173-.127-.3q-.127-.125-.302-.125t-.3.126t-.127.299v4.984q0 .344.233.576t.575.232h2.546q.178 0 .298-.121q.121-.121.121-.299t-.12-.298t-.299-.12z");
}

</style>
