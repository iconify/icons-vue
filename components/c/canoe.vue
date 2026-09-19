<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pgl5y72wm.css';
import '../../css/m/mgti0_btg.css';
import '../../css/a/awf6kabnh.css';
import '../../css/s/st53awbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="pgl5y72wm"/><path class="mgti0_btg"/><path class="awf6kabnh"/><path class="st53awbpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:canoe" /></template>
