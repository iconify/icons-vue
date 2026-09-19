<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kw8enf78q.css';
import '../../css/v/vkfcnv4wi.css';
import '../../css/q/qbzh04khg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kw8enf78q"/><path class="vkfcnv4wi"/><path class="qbzh04khg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:camera-smile-02" /></template>
