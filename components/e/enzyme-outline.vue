<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hrceo_b_n.css';
import '../../css/m/mnzk3bcrc.css';
import '../../css/v/vithtcboi.css';
import '../../css/r/r5-ki1pcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="hrceo_b_n"/><path class="mnzk3bcrc"/><path class="vithtcboi"/><path clip-rule="evenodd" class="r5-ki1pcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:enzyme-outline" /></template>
