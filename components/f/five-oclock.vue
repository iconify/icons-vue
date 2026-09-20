<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnclpcc6m.css';
import '../../css/k/kso7adcaj.css';
import '../../css/e/es25eccir.css';
import '../../css/i/ij2x_72vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGFeFs0drr" class="gnclpcc6m"/></defs><g class="kso7adcaj"><circle class="es25eccir"/><use href="#SVGFeFs0drr"/></g><g class="ij2x_72vy"><circle class="es25eccir"/><use href="#SVGFeFs0drr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:five-oclock" /></template>
