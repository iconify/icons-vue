<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopnm44um.css';
import '../../css/l/ljdas5boi.css';
import '../../css/e/e74gmob1x.css';
import '../../css/r/ragiu_dif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="gopnm44um"><rect class="ljdas5boi"/><rect class="e74gmob1x"/><path class="ragiu_dif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:chinese" /></template>
