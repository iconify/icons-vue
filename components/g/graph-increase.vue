<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/m/mif2vhb3d.css';
import '../../css/i/i35t25ucf.css';
import '../../css/h/hjltgiuuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="mif2vhb3d"/><path class="i35t25ucf"/><path class="hjltgiuuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:graph-increase" /></template>
