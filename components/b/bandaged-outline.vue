<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/e/eqg_32bbr.css';
import '../../css/p/pgwj559ot.css';
import '../../css/d/deucknbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="eqg_32bbr"/><path class="pgwj559ot"/><path class="deucknbez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:bandaged-outline" /></template>
