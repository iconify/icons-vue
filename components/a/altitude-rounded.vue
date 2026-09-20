<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_wp7wbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:altitude-rounded" /></template>
<style>
.y_wp7wbby {
  fill: currentColor;
  d: path("M4.52 20.192q-.51 0-.728-.444t.081-.848l2.577-3.46q.13-.161.295-.242t.351-.08q.187 0 .351.08q.165.08.295.243l2.524 3.355q.134.177.323.208t.365-.104t.21-.335t-.106-.379l-.858-1.144q-.161-.217-.171-.484q-.01-.268.152-.485l3.269-4.363q.13-.162.295-.243t.351-.08t.351.08q.165.081.295.242l5.385 7.191q.298.404.08.848t-.726.444zm14.123-8.335q-.143-.143-.143-.357V7.108l-1.771 1.746q-.14.14-.338.134q-.199-.007-.345-.154q-.14-.14-.14-.344t.14-.344l2.389-2.369q.242-.243.565-.243t.566.243l2.388 2.37q.146.145.137.343q-.01.198-.156.364q-.146.146-.347.146t-.347-.146L19.5 7.114V11.5q0 .214-.143.357T19 12t-.357-.143");
}

</style>
