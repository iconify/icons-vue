<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/liev_vb3r.css';
import '../../css/k/kso7adcaj.css';
import '../../css/e/es25eccir.css';
import '../../css/i/ij2x_72vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGWyWaeepJ" class="liev_vb3r"/></defs><g class="kso7adcaj"><circle class="es25eccir"/><use href="#SVGWyWaeepJ"/></g><g class="ij2x_72vy"><circle class="es25eccir"/><use href="#SVGWyWaeepJ"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:four-oclock" /></template>
