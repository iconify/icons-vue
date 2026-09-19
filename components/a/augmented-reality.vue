<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/h/h_cgl-bdl.css';
import '../../css/d/d-5qcb7mz.css';
import '../../css/w/w4xii1z6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="h_cgl-bdl"/><path class="d-5qcb7mz"/><path class="w4xii1z6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:augmented-reality" /></template>
