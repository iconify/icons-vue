<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/yxub042gf.css';
import '../../css/k/k-6h5bc3a.css';
import '../../css/c/cqj5tpb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="yxub042gf"/><path class="k-6h5bc3a"/><path class="cqj5tpb-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cart-linear" /></template>
