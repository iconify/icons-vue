<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yrncfdc7x.css';
import '../../css/k/kowma_bmi.css';
import '../../css/t/t5lqdhfmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":301,"height":225};
const content = `<g class="ft5dv1b6b"><path class="yrncfdc7x"/><path class="kowma_bmi"/><path class="t5lqdhfmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:ga" /></template>
