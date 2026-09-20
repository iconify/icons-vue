<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcmoe4kyy.css';
import '../../css/l/ld8_l_m_x.css';
import '../../css/p/pyo091bsc.css';
import '../../css/c/c8afke3ti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":440,"height":438};
const content = `<defs><linearGradient id="SVG9JK7sSPy" x1="86" x2="289" y1="36" y2="420" gradientUnits="userSpaceOnUse"><stop offset="0" class="vcmoe4kyy"/><stop offset=".52" class="ld8_l_m_x"/><stop offset="1" class="pyo091bsc"/></linearGradient></defs><path stroke="url(#SVG9JK7sSPy)" class="c8afke3ti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:genstory" /></template>
