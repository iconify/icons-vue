<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n4p47rbwq.css';
import '../../css/i/iok8bk2rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="n4p47rbwq"/><path clip-rule="evenodd" class="iok8bk2rv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:intravenous-bag2x-outline" /></template>
