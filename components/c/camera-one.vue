<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/y/yez7skblq.css';
import '../../css/n/n6bczebbq.css';
import '../../css/h/h2uo0wbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="yez7skblq"/><circle class="n6bczebbq"/><path class="h2uo0wbmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:camera-one" /></template>
