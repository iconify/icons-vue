<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sb7r65ztw.css';
import '../../css/p/ptgid_4ay.css';
import '../../css/m/m89qgbkka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="sb7r65ztw"/><path clip-rule="evenodd" class="ptgid_4ay"/><path class="m89qgbkka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chart-death-rate-increasing" /></template>
