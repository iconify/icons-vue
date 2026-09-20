<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1oqqgxeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:code-off-outline-rounded" /></template>
<style>
.m1oqqgxeh {
  fill: currentColor;
  d: path("m4.114 12.006l4.24 4.24q.14.14.15.345q.01.203-.15.363t-.354.16t-.354-.16l-4.388-4.389q-.131-.13-.184-.267q-.053-.136-.053-.298t.053-.298t.184-.267l3.375-3.376l-3.539-3.538q-.146-.146-.156-.347t.156-.366t.357-.166t.357.166l16.384 16.384q.146.147.156.345t-.156.363t-.357.166q-.19 0-.356-.166L7.346 8.773zm13.427 2.526q0-.191.165-.357l2.18-2.18l-4.24-4.241q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16l4.388 4.389q.131.13.184.267t.053.298t-.053.298t-.184.268l-2.328 2.328q-.147.147-.345.153t-.363-.158q-.165-.166-.165-.357");
}

</style>
