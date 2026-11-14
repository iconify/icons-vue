<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8daa422k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-holder" /></template>
<style>
.v8daa422k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.128 9.994q.21-.264.373-.559t.275-.614q.111-.319.168-.651Q16 7.837 16 7.5q0-.197-.019-.392q-.02-.196-.058-.388q-.038-.193-.095-.381t-.132-.37q-.076-.181-.168-.355q-.093-.173-.202-.336t-.234-.316q-.125-.151-.264-.29t-.29-.264t-.316-.234q-.163-.109-.336-.202q-.174-.092-.355-.168q-.182-.075-.37-.132t-.381-.095t-.388-.058T12 3.5t-.392.019q-.196.02-.388.058q-.193.038-.381.095t-.37.132q-.181.076-.355.168q-.173.093-.336.202t-.316.234q-.151.125-.29.264t-.264.29t-.234.316q-.109.163-.202.336q-.092.174-.168.355q-.075.182-.132.37t-.095.381t-.058.388T8 7.5q0 .187.017.373t.053.37q.034.184.086.364q.052.179.12.354q.068.174.153.341t.183.325q.1.158.214.307q.113.148.241.285q.127.137.266.262t.29.236t.31.208q.161.096.329.178t.344.146t.356.114q.18.048.365.08q.184.031.37.046M4 21c0-3.917 3.357-6.396 7.723-6.497M14.5 12.75h7v9h-7Zm2.25 0v9m1.75-6.25h1.25");
}

</style>
