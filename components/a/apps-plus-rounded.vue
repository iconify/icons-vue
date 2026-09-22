<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bci4zob4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:apps-plus-rounded" /></template>
<style>
.bci4zob4j {
  fill: currentColor;
  d: path("M17 7.808h-2.5q-.213 0-.356-.144T14 7.307t.144-.356t.356-.143H17v-2.5q0-.213.144-.357t.357-.143t.356.143t.143.357v2.5h2.5q.213 0 .356.144q.144.143.144.356t-.144.356t-.356.144H18v2.5q0 .212-.144.356t-.357.144t-.356-.144t-.143-.356zM12 19h8.192q.344 0 .576-.232t.232-.576v-4.184q0-.356-.232-.586q-.233-.23-.576-.23H12q-.343 0-.575.232t-.233.576v4.185q0 .356.233.585T12 19m-8.192-8.192H11q.343 0 .576-.232t.232-.576V5.815q0-.355-.232-.585T11 5H3.808q-.343 0-.576.232T3 5.808v4.185q0 .355.232.585t.576.23m0 8.192h4.185q.355 0 .585-.232q.23-.233.23-.576v-4.184q0-.356-.232-.586q-.233-.23-.576-.23H3.815q-.355 0-.585.232T3 14v4.185q0 .356.232.585t.576.23");
}

</style>
