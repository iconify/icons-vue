<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/k/kpwbe7bbo.css';
import '../../css/p/p53xcyb3q.css';
import '../../css/x/xyob36bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kpwbe7bbo"/><path class="p53xcyb3q"/><path class="xyob36bij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-candlestick-sharp-two-tone" /></template>
