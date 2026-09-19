<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t88j5qbod.css';
import '../../css/g/g4jfx9s0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="t88j5qbod"/><path clip-rule="evenodd" class="g4jfx9s0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:low-bars-negative" /></template>
