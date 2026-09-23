<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/l/lak79pbge.css';
import '../../css/r/rvil501-p.css';
import '../../css/u/uecn1lb3p.css';
import '../../css/o/omi2j1bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lak79pbge"/><path class="rvil501-p"/><path class="uecn1lb3p"/><path class="omi2j1bhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-no-axes-combined-sparkles-sharp-two-tone" /></template>
