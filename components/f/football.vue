<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/g/geju8gabu.css';
import '../../css/e/ehotb-rys.css';
import '../../css/z/zwy-7u4cy.css';
import '../../css/q/qp26irmvt.css';
import '../../css/m/mlirullni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="geju8gabu"/><path class="ehotb-rys"/><path class="zwy-7u4cy"/><path class="qp26irmvt"/><path class="mlirullni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:football" /></template>
