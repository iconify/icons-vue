<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oqtbvlb1g.css';
import '../../css/r/rbof6kbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="oqtbvlb1g"/><path clip-rule="evenodd" class="rbof6kbxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-pressure-monitor-outline" /></template>
