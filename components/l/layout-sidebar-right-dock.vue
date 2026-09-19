<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lrlan6lvw.css';
import '../../css/l/l_l4dubrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="lrlan6lvw"/><path clip-rule="evenodd" class="l_l4dubrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-sidebar-right-dock" /></template>
