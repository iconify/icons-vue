<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu-s-mrny.css';
import '../../css/y/ypecetwke.css';
import '../../css/w/wqngztpuq.css';
import '../../css/t/ts68x3biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gu-s-mrny"/><path class="ypecetwke"/><path class="wqngztpuq"/><path class="ts68x3biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-candlestick-48" /></template>
