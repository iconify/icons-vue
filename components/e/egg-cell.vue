<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vhrzp3m4f.css';
import '../../css/n/nakj5ubjo.css';
import '../../css/y/yriqevbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="vhrzp3m4f"/><path clip-rule="evenodd" class="nakj5ubjo"/><path clip-rule="evenodd" class="yriqevbyr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:egg-cell" /></template>
