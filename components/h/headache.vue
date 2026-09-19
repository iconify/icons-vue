<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vcj0oe52h.css';
import '../../css/m/mn2im8yde.css';
import '../../css/m/mcxp28brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="vcj0oe52h"/><path clip-rule="evenodd" class="mn2im8yde"/><path class="mcxp28brc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:headache" /></template>
