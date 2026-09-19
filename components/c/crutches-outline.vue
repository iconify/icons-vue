<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dw39a-bwv.css';
import '../../css/r/rxx21sbup.css';
import '../../css/w/wyubm_1dg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="dw39a-bwv"/><path clip-rule="evenodd" class="rxx21sbup"/><path clip-rule="evenodd" class="wyubm_1dg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:crutches-outline" /></template>
