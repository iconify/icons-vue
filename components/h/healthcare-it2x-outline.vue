<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xf1a6wbgm.css';
import '../../css/m/mgg26ff3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="xf1a6wbgm"/><path clip-rule="evenodd" class="mgg26ff3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:healthcare-it2x-outline" /></template>
