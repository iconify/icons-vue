<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7v7hhixj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:assignment-returned-rounded" /></template>
<style>
.h7v7hhixj {
  fill: currentColor;
  d: path("m11.5 13.342l-1.746-1.701q-.16-.141-.351-.15t-.361.16q-.155.155-.155.349t.16.354l2.388 2.388q.242.243.565.243t.566-.243l2.388-2.388q.14-.14.153-.341t-.147-.361q-.147-.146-.348-.149t-.366.138L12.5 13.342v-4.15q0-.212-.144-.356t-.357-.144t-.356.144t-.143.356zM5.616 20q-.667 0-1.141-.475T4 18.386V5.615q0-.666.475-1.14T5.615 4h4.7q-.136-.766.367-1.383Q11.184 2 12.01 2t1.328.617T13.685 4h4.7q.666 0 1.14.475T20 5.615v12.77q0 .666-.475 1.14t-1.14.475zm6.922-15.77q.212-.213.212-.538t-.212-.537T12 2.942t-.537.213t-.213.537t.213.538t.537.212t.538-.212");
}

</style>
