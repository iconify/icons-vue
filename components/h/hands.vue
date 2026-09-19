<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/e/e9uruk8bl.css';
import '../../css/z/z7xy-3w1r.css';
import '../../css/v/v1phh24wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><circle class="e9uruk8bl"/><path class="z7xy-3w1r"/><path class="v1phh24wk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:hands" /></template>
