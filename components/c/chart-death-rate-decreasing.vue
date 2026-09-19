<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yr9lhub6p.css';
import '../../css/l/l-6s2cixh.css';
import '../../css/t/terzj2bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="yr9lhub6p"/><path clip-rule="evenodd" class="l-6s2cixh"/><path class="terzj2bry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-death-rate-decreasing" /></template>
