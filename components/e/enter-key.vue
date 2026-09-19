<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/j/jywzibzfz.css';
import '../../css/f/fw8rx6b9c.css';
import '../../css/c/cuh8gyztp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="jywzibzfz"/><path class="fw8rx6b9c"/><path class="cuh8gyztp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:enter-key" /></template>
