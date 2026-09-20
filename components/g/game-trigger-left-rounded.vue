<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir0i2hoby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-trigger-left-rounded" /></template>
<style>
.ir0i2hoby {
  fill: currentColor;
  d: path("M8.66 14.289v-4.96q0-.173-.126-.3q-.126-.125-.301-.125t-.302.126t-.127.299v4.979q0 .343.232.575t.576.232h2.58q.182 0 .298-.115t.116-.296t-.116-.298t-.298-.118zm5.71-4.558v4.96q0 .172.125.298t.301.126t.302-.126t.127-.299V9.73h1.52q.181 0 .297-.114q.116-.115.116-.296t-.116-.299t-.298-.117h-3.913q-.182 0-.298.115t-.116.296t.116.299t.298.117zM3 17.384V8.27q0-1.356.977-2.322t2.35-.966h11.346q1.373 0 2.35.966T21 8.269v9.116q0 .666-.474 1.14T19.385 19H4.615q-.666 0-1.14-.475T3 17.386");
}

</style>
