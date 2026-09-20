<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zb8-kubni.css';
import '../../css/w/wq2ys5qgg.css';
import '../../css/m/mj0570bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zb8-kubni"/><path class="wq2ys5qgg"/><path class="mj0570bpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:file-plus" /></template>
