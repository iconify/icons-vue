<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/y/yez7skblq.css';
import '../../css/v/vydujvb8s.css';
import '../../css/h/h2uo0wbmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="yez7skblq"/><circle class="vydujvb8s"/><path class="h2uo0wbmx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:camera-one" /></template>
