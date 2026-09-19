<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/n/nalfbrbnz.css';
import '../../css/p/p620f_0bx.css';
import '../../css/p/p5eipvbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><circle class="nalfbrbnz"/><path class="p620f_0bx"/><path class="p5eipvbsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:fm" /></template>
