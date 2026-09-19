<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/uxetctbkk.css';
import '../../css/h/hu81nxnew.css';
import '../../css/l/lifqzczhe.css';
import '../../css/s/s_k11pbna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="uxetctbkk"/><path class="hu81nxnew"/><path class="lifqzczhe"/><path class="s_k11pbna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:battery-charging" /></template>
