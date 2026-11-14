<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kysymrbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hormone" /></template>
<style>
.kysymrbgm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.75 9.103q.188.072.375.18l2.397 1.384q1.125.65 1.125 1.949v2.768q0 1.299-1.125 1.949l-2.397 1.384q-1.125.649-2.25 0l-2.397-1.384q-.193-.112-.353-.243q-.16.131-.353.243l-2.397 1.384q-1.125.649-2.25 0l-2.397-1.384q-1.125-.65-1.125-1.949v-2.768q0-1.299 1.125-1.949l2.397-1.384q1.125-.649 2.25 0l2.397 1.384q.193.112.353.243q.16-.131.353-.243l2.397-1.384q.187-.108.375-.18V6.5q0-.093.023-.182q.022-.09.066-.172q.043-.082.106-.15q.062-.069.139-.12l3-2q.061-.041.13-.069q.068-.028.14-.043t.147-.014q.074 0 .146.015q.073.014.141.042t.129.07t.114.093q.052.053.093.114q.083.124.112.27t-.001.293q-.029.146-.112.27t-.207.207L16.75 6.901z");
}

</style>
