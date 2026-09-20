<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lxxbevx9y.css';
import '../../css/c/c4g_yjbwf.css';
import '../../css/v/vwva7rs6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="lxxbevx9y"/><path clip-rule="evenodd" class="c4g_yjbwf"/><path clip-rule="evenodd" class="vwva7rs6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:house" /></template>
