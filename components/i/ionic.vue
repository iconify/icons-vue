<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thpy47d_f.css';
import '../../css/e/e8x6debrh.css';
import '../../css/u/u96hv1wct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<g class="thpy47d_f"><circle class="e8x6debrh"/><path class="u96hv1wct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:ionic" /></template>
