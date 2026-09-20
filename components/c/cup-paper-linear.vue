<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c020a4bmu.css';
import '../../css/t/tef83mb6y.css';
import '../../css/t/tk6t9fbyh.css';
import '../../css/j/jxdwkm1he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c020a4bmu"/><path class="tef83mb6y"/><path class="tk6t9fbyh"/><path class="jxdwkm1he"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cup-paper-linear" /></template>
