<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h__9ti67x.css';
import '../../css/h/hj92n7xau.css';
import '../../css/j/j6hcrujfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="h__9ti67x"/><path clip-rule="evenodd" class="hj92n7xau"/><path class="j6hcrujfg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:magnifying-glass" /></template>
