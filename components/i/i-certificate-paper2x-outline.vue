<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qo-cleo8d.css';
import '../../css/n/nt8fw_bxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="qo-cleo8d"/><path clip-rule="evenodd" class="nt8fw_bxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:i-certificate-paper2x-outline" /></template>
