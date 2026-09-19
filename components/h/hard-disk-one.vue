<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/q/qzkhf9znl.css';
import '../../css/g/grd5-pe1q.css';
import '../../css/m/mn9q66bmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="qzkhf9znl"/><path class="grd5-pe1q"/><path class="mn9q66bmt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:hard-disk-one" /></template>
