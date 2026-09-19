<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j5eqa4bgt.css';
import '../../css/l/l-6s2cixh.css';
import '../../css/y/y0z3zppyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="j5eqa4bgt"/><path clip-rule="evenodd" class="l-6s2cixh"/><path class="y0z3zppyt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-death-rate-stable" /></template>
