<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/r/rh2ocrb7y.css';
import '../../css/s/squ55obdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><rect transform="rotate(-45 8 8)" class="rh2ocrb7y"/><path class="squ55obdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:eraser-stroke-16" /></template>
