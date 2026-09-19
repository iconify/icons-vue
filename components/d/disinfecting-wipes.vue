<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w2inmo5zg.css';
import '../../css/b/bc7uu5x5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="w2inmo5zg"/><path clip-rule="evenodd" class="bc7uu5x5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:disinfecting-wipes" /></template>
