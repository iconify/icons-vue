<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf1axp80z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dashboard-2-add-rounded" /></template>
<style>
.yf1axp80z {
  fill: currentColor;
  d: path("M3.808 19h4.185q.355 0 .585-.232q.23-.233.23-.576v-4.184q0-.356-.232-.586q-.233-.23-.576-.23H3.815q-.355 0-.585.232T3 14v4.185q0 .356.232.585t.576.23m0-8.192H11q.343 0 .576-.232t.232-.576V5.815q0-.355-.232-.585T11 5H3.808q-.343 0-.576.232T3 5.808v4.185q0 .355.232.585t.576.23M12 19h8.192q.344 0 .576-.232t.232-.576v-4.184q0-.356-.232-.586q-.233-.23-.576-.23H12q-.343 0-.575.232t-.233.576v4.185q0 .356.233.585T12 19m6-8.192q-1.671 0-2.835-1.165Q14 8.48 14 6.808t1.165-2.836T18 2.808t2.836 1.164T22 6.808q0 1.67-1.164 2.835Q19.67 10.808 18 10.808m-.385-3.616v2.116q0 .154.116.269q.115.115.269.115t.27-.115t.114-.27V7.193H20.5q.154 0 .27-.111q.114-.112.114-.273t-.115-.273t-.269-.112h-2.116V4.308q0-.154-.115-.27q-.115-.115-.269-.115t-.27.116t-.114.269v2.115H15.5q-.154 0-.27.112q-.114.111-.114.273t.115.273t.269.111z");
}

</style>
