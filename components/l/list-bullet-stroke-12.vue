<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sacdn40yp.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f96l9acmb.css';
import '../../css/c/c6auvpuvc.css';
import '../../css/e/edlkufbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="sacdn40yp"/><g class="cuyn6tgcc"><circle class="f96l9acmb"/><circle class="c6auvpuvc"/><circle class="edlkufbty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:list-bullet-stroke-12" /></template>
