<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n8ri4r_8m.css';
import '../../css/w/w7d7mlbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="n8ri4r_8m"/><path clip-rule="evenodd" class="w7d7mlbak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:health-literacy2x-outline" /></template>
