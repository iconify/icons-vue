<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hgs51yb0o.css';
import '../../css/m/mb35h0b4e.css';
import '../../css/k/kq6uq6h8w.css';
import '../../css/e/e0cmz0boh.css';
import '../../css/z/zr35ecbmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hgs51yb0o"/><path class="mb35h0b4e"/><path class="kq6uq6h8w"/><path class="e0cmz0boh"/><path class="zr35ecbmr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-chart-2-linear" /></template>
