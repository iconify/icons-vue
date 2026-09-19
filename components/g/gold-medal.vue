<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/m66g3kb5k.css';
import '../../css/g/g00mx43ai.css';
import '../../css/i/ij785dbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="m66g3kb5k"/><path class="g00mx43ai"/><path class="ij785dbcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:gold-medal" /></template>
