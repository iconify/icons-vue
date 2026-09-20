<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8o025bvy.css';
import '../../css/x/xmbv1lser.css';
import '../../css/q/qc4q2o3mb.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/v/v3wlrwo_l.css';
import '../../css/o/oz7n92_8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="e8o025bvy"/><path class="xmbv1lser"/><path class="qc4q2o3mb"/><g class="ij2x_72vy"><path class="v3wlrwo_l"/><path class="oz7n92_8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:dizzy" /></template>
