<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bne9y_b7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blocker-contact" /></template>
<style>
.bne9y_b7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.52 10.607q.173-.141.329-.299q.156-.159.294-.333t.255-.364t.213-.39t.169-.412q.072-.21.122-.427q.049-.217.073-.438Q16 7.723 16 7.5q0-.197-.019-.392q-.02-.196-.058-.388q-.038-.193-.095-.381t-.132-.37q-.076-.181-.168-.355q-.093-.173-.202-.336t-.234-.316q-.125-.151-.264-.29t-.29-.264t-.316-.234q-.163-.109-.336-.202q-.174-.092-.355-.168q-.182-.075-.37-.132t-.381-.095t-.388-.058T12 3.5q-.222 0-.442.024q-.22.025-.436.074t-.426.12q-.209.073-.409.168q-.201.094-.389.211q-.189.116-.363.253q-.175.136-.333.291t-.299.327M4.5 21c0-3.98 2.738-6.005 6.139-6.419M3.5 3.5l17 17");
}

</style>
