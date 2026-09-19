<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ifw-3tbef.css';
import '../../css/k/kcbnqacwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="ifw-3tbef"/><path clip-rule="evenodd" class="kcbnqacwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:contraceptive-diaphragm2x-outline" /></template>
