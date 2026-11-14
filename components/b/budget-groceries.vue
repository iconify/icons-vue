<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jk4169buj"/><path class="pbrf5747u"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:budget-groceries" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jk4169buj {
  d: path("M11.24 18.5H6.349q-.144 0-.286-.024q-.142-.023-.278-.07q-.137-.046-.263-.114q-.127-.068-.241-.156t-.212-.194q-.099-.105-.178-.225q-.08-.12-.139-.251q-.058-.132-.095-.271l-1.579-6q-.025-.097-.04-.196t-.017-.199q-.003-.1.006-.2q.008-.099.028-.197t.051-.194q.031-.095.073-.186t.093-.176t.112-.165t.131-.151t.147-.136q.078-.063.162-.117t.174-.098t.184-.078t.192-.056t.197-.035Q4.67 9 4.77 9h14.46q.1 0 .199.011q.1.012.197.035q.098.022.192.056t.184.078t.174.098t.162.117t.147.136q.069.071.131.151q.061.079.112.165q.052.085.093.176q.042.091.073.186q.031.096.051.194t.028.197q.009.1.006.2t-.017.199q-.015.099-.04.196l-.319 1.211M4.5 9V7a2.75 2.75 0 0 1 2.75-2.75h1.5A2.75 2.75 0 0 1 11.5 7v2m2.75 0c0-5.5 5.5-5.5 5.5 0");
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.pbrf5747u {
  d: path("M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
