<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjfsv9bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coal-phase-out" /></template>
<style>
.xjfsv9bek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.372 19.395q-.289.105-.597.105H8.582q-.121 0-.241-.017q-.121-.016-.237-.049q-.117-.033-.228-.082t-.214-.113t-.197-.141t-.175-.167t-.151-.19t-.123-.208l-2.625-5.25q-.091-.182-.138-.381q-.047-.198-.047-.402t.047-.402t.138-.381l1.118-2.236m3.556-4.342l4.221-.974q.17-.039.344-.044t.346.025t.334.092t.309.156l4.202 2.674q.16.102.294.235q.134.134.237.293t.169.336t.093.365l.762 5.337q.029.202.011.405t-.083.396t-.172.367t-.251.317l-.435.435M3.5 3.5l17 17");
}

</style>
