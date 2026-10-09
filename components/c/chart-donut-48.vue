<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpeu_j1mo.css';
import '../../css/c/cmhnqibcc.css';
import '../../css/w/wqsnrac2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tpeu_j1mo"/><path class="cmhnqibcc"/><path class="wqsnrac2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-donut-48" /></template>
