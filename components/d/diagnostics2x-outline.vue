<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f2-lv5boq.css';
import '../../css/o/o34fr3bgc.css';
import '../../css/v/v52a6hbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="f2-lv5boq"/><path clip-rule="evenodd" class="o34fr3bgc"/><path class="v52a6hbjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:diagnostics2x-outline" /></template>
