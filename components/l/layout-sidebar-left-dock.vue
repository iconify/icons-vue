<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tazpy2b7v.css';
import '../../css/j/j_t6d7uhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="tazpy2b7v"/><path clip-rule="evenodd" class="j_t6d7uhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-sidebar-left-dock" /></template>
