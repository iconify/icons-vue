<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dmm2q7biv.css';
import '../../css/k/k4-raktki.css';
import '../../css/e/ep9_um9bz.css';
import '../../css/c/cfj55dbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="dmm2q7biv"/><path clip-rule="evenodd" class="k4-raktki"/><path class="ep9_um9bz"/><path clip-rule="evenodd" class="cfj55dbec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:loinc2x-outline" /></template>
