<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/ka5pt8bhv.css';
import '../../css/n/nfbfp3s5x.css';
import '../../css/h/hj_z2vbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ka5pt8bhv"/><path class="nfbfp3s5x"/><path clip-rule="evenodd" class="hj_z2vbmb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:low-income-level-outline-24px" /></template>
