<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/c/cp-ocb-3y.css';
import '../../css/y/yof8mbb2y.css';
import '../../css/j/jl-543bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="cp-ocb-3y"/><path class="yof8mbb2y"/><path class="jl-543bif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:honey" /></template>
