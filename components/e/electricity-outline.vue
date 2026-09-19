<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lzcxp6rgp.css';
import '../../css/z/zg-d3i4so.css';
import '../../css/d/d0t86vbpx.css';
import '../../css/x/xky54bc0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="lzcxp6rgp"/><path clip-rule="evenodd" class="zg-d3i4so"/><path class="d0t86vbpx"/><path clip-rule="evenodd" class="xky54bc0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:electricity-outline" /></template>
