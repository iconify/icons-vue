<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/n/nagtiqban.css';
import '../../css/t/to2zchgfu.css';
import '../../css/c/cswwhib7x.css';
import '../../css/x/xjdiaqb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="nagtiqban"/><circle class="to2zchgfu"/><circle class="cswwhib7x"/><circle class="xjdiaqb1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:blockchain" /></template>
