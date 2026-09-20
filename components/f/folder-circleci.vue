<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dypv3-mdc.css';
import '../../css/j/jrywsebcn.css';
import '../../css/e/eoh-kmiad.css';
import '../../css/u/un29wccgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dypv3-mdc"/><g class="jrywsebcn"><path class="eoh-kmiad"/><circle class="un29wccgo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-circleci" /></template>
