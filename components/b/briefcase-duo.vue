<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sjyu3g0yf.css';
import '../../css/w/w5l3mbitk.css';
import '../../css/p/pl_50btdl.css';
import '../../css/t/t_w36ccaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="sjyu3g0yf"/><path class="w5l3mbitk"/><path class="pl_50btdl"/><path class="t_w36ccaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:briefcase-duo" /></template>
