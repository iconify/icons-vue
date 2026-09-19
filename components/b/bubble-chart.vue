<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/h/hz_qsuwka.css';
import '../../css/d/dj487cy_p.css';
import '../../css/w/wano3i20j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="hz_qsuwka"/><circle class="dj487cy_p"/><circle class="wano3i20j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:bubble-chart" /></template>
