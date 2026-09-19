<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/klv2o9buk.css';
import '../../css/l/l-6s2cixh.css';
import '../../css/t/terzj2bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="klv2o9buk"/><path clip-rule="evenodd" class="l-6s2cixh"/><path class="terzj2bry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-death-rate-decreasing-outline" /></template>
