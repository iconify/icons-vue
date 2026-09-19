<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t3c766b8e.css';
import '../../css/d/dmu7i8byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="t3c766b8e"/><path clip-rule="evenodd" class="dmu7i8byd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:integrated-data-and-research2x-outline" /></template>
