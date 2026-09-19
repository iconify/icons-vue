<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/z/zbsa-ujvj.css';
import '../../css/e/elnthojgr.css';
import '../../css/p/pcfefwb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="zbsa-ujvj"/><path class="elnthojgr"/><path class="pcfefwb7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:kettle-one" /></template>
