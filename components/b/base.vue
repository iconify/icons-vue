<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zojluwred"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:base" /></template>
<style>
.zojluwred {
  fill: var(--svg-color--00f, #00f);
  d: path("M3 4.706c0-.585 0-.877.11-1.101c.106-.215.28-.39.496-.495C3.83 3 4.122 3 4.706 3h14.588c.585 0 .876 0 1.101.11c.215.105.389.28.494.495c.111.225.111.517.111 1.101v14.588c0 .585 0 .876-.11 1.101c-.106.215-.28.389-.495.494c-.225.111-.517.111-1.101.111H4.706c-.585 0-.876 0-1.101-.11a1.08 1.08 0 0 1-.494-.495C3 20.17 3 19.878 3 19.294z");
}

</style>
