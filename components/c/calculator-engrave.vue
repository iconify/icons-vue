<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/etlx3qbwc.css';
import '../../css/x/xfcab7bto.css';
import '../../css/l/l7umh3bwe.css';
import '../../css/n/nj6yhupln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="etlx3qbwc wm-k"/><path class="wm-shadow xfcab7bto"/><path class="l7umh3bwe wm-k"/><path class="nj6yhupln wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calculator-engrave" /></template>
