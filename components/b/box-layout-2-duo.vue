<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zhms9dvjt.css';
import '../../css/r/rpt1xmbzs.css';
import '../../css/l/li-7n8b6p.css';
import '../../css/r/r4nx58bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zhms9dvjt"/><path clip-rule="evenodd" class="rpt1xmbzs"/><path class="li-7n8b6p"/><path clip-rule="evenodd" class="r4nx58bsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box-layout-2-duo" /></template>
