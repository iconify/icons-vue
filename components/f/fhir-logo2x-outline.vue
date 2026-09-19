<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nnjq4tb9x.css';
import '../../css/c/c7flqrulw.css';
import '../../css/l/lx0v1-bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="nnjq4tb9x"/><path clip-rule="evenodd" class="c7flqrulw"/><path class="lx0v1-bxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:fhir-logo2x-outline" /></template>
