<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/a/am4lb-bdv.css';
import '../../css/l/ln7fn5cus.css';
import '../../css/s/scyn38bvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="am4lb-bdv"/><path class="ln7fn5cus"/><path class="scyn38bvf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:frigate" /></template>
