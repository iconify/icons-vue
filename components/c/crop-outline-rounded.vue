<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjfgkobux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-outline-rounded" /></template>
<style>
.jjfgkobux {
  fill: currentColor;
  d: path("M17.5 22v-3.5H7.116q-.691 0-1.153-.462T5.5 16.884V6.5H2q-.213 0-.356-.144T1.5 5.999t.144-.356T2 5.5h3.5V2q0-.213.144-.356t.357-.144t.356.144T6.5 2v14.885q0 .23.192.423t.423.192H22q.213 0 .356.144t.144.357t-.144.356T22 18.5h-3.5V22q0 .213-.144.356t-.357.144t-.356-.144T17.5 22m0-5.5V7.116q0-.231-.192-.424t-.424-.192H7.5v-1h9.385q.69 0 1.153.463t.462 1.153V16.5z");
}

</style>
