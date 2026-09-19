<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/i/i72f4jbac.css';
import '../../css/a/abtri_fkx.css';
import '../../css/s/sfy1x5b8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="i72f4jbac"/><path class="abtri_fkx"/><path class="sfy1x5b8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:lipstick" /></template>
