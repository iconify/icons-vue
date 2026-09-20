<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6rz3ccuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-mac-outline-rounded" /></template>
<style>
.t6rz3ccuk {
  fill: currentColor;
  d: path("M11.154 17.346H4.616q-.691 0-1.153-.462T3 15.73V5.616q0-.691.463-1.153T4.615 4h14.77q.69 0 1.152.463T21 5.616V15.73q0 .69-.463 1.153t-1.153.462h-6.538l1.773 1.773q.05.05.112.273v.224q0 .161-.112.273t-.273.111H9.542q-.111 0-.192-.08t-.08-.193v-.385q0-.05.08-.192zM4 14.846h16v-9.23q0-.231-.192-.424T19.385 5H4.615q-.23 0-.423.192T4 5.616zm0 0V5z");
}

</style>
