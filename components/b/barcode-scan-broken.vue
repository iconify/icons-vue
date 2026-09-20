<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v7vsmrbcy.css';
import '../../css/i/i4kkq_9oy.css';
import '../../css/m/msxlffrej.css';
import '../../css/h/htjp6vbcb.css';
import '../../css/o/oja1tdbnv.css';
import '../../css/q/qsmbhrb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v7vsmrbcy"/><path class="i4kkq_9oy"/><path class="msxlffrej"/><path class="htjp6vbcb"/><rect class="oja1tdbnv"/><rect class="qsmbhrb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:barcode-scan-broken" /></template>
