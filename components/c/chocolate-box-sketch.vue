<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dqywfr4sz.css';
import '../../css/o/oj5c48bry.css';
import '../../css/t/tf3d3bb_b.css';
import '../../css/z/zoxatjh8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dqywfr4sz"/><path class="oj5c48bry wm-k"/><path class="tf3d3bb_b wm-k"/><path class="wm-a zoxatjh8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chocolate-box-sketch" /></template>
