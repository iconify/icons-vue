<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h6id0lbwz.css';
import '../../css/m/mxns_2bzi.css';
import '../../css/s/shbvfpb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="h6id0lbwz"/><path class="mxns_2bzi"/><path class="shbvfpb7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:doctor-male" /></template>
