<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mu9bddh4x.css';
import '../../css/e/ekyn8cc0w.css';
import '../../css/c/cnzf-abva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="mu9bddh4x"/><path class="ekyn8cc0w"/><path class="cnzf-abva"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layers" /></template>
