<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7hxt4kvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:campaign" /></template>
<style>
.h7hxt4kvb {
  fill: currentColor;
  d: path("M17.923 12.5v-1h3.23v1zm1.085 6.462l-2.585-1.939l.623-.792l2.585 1.938zm-2.039-11.27l-.623-.792l2.585-1.939l.623.793zM5.5 17.962v-3.808H4.462q-.671 0-1.144-.472t-.472-1.143v-1.077q0-.671.472-1.144t1.143-.472h3.731L12.154 7.5v9l-3.962-2.346H6.5v3.808zm8.423-3.073V9.112q.502.465.809 1.222T15.038 12t-.306 1.666t-.809 1.222");
}

</style>
