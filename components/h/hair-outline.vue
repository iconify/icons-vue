<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nhold6bcw.css';
import '../../css/d/dk55ffbep.css';
import '../../css/d/d5xw9nb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="nhold6bcw"/><path clip-rule="evenodd" class="dk55ffbep"/><path class="d5xw9nb-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:hair-outline" /></template>
