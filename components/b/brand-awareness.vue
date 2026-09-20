<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1-r1_zja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:brand-awareness" /></template>
<style>
.m1-r1_zja {
  fill: currentColor;
  d: path("M15.654 12.5v-1h3.23v1zm1.085 6.462l-2.585-1.939l.623-.792l2.585 1.938zM14.7 7.692l-.623-.792l2.585-1.939l.623.793zM4.116 14v-4h3.423l3.577-3.577v11.154L7.539 14z");
}

</style>
