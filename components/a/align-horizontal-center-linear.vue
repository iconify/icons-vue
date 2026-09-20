<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/ohw_5actf.css';
import '../../css/r/rd5_q5bmh.css';
import '../../css/y/y2b_7cbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ohw_5actf"/><path class="rd5_q5bmh"/><path class="y2b_7cbos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-horizontal-center-linear" /></template>
