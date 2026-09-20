<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5botrbho.css';
import '../../css/k/kso7adcaj.css';
import '../../css/e/es25eccir.css';
import '../../css/i/ij2x_72vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGUZBmacQu" class="u5botrbho"/></defs><g class="kso7adcaj"><circle class="es25eccir"/><use href="#SVGUZBmacQu"/></g><g class="ij2x_72vy"><circle class="es25eccir"/><use href="#SVGUZBmacQu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:five-thirty" /></template>
