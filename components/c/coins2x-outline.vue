<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jt50z3bql.css';
import '../../css/i/ij34_2wnx.css';
import '../../css/m/mgfuygb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="jt50z3bql"/><path clip-rule="evenodd" class="ij34_2wnx"/><path clip-rule="evenodd" class="mgfuygb4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:coins2x-outline" /></template>
