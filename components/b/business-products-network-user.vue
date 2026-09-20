<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkdtjjbjw.css';
import '../../css/d/dt3455rte.css';
import '../../css/w/wd_zv6bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lkdtjjbjw"/><path class="dt3455rte"/><path class="wd_zv6bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:business-products-network-user" /></template>
