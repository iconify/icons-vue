<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyyebzbnj.css';
import '../../css/w/wz2svgbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tyyebzbnj"/><path class="wz2svgbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-combo-48" /></template>
