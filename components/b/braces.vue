<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/anma4zbmz.css';
import '../../css/a/ajiukk8qu.css';
import '../../css/y/y_8f2ac4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="anma4zbmz"/><path class="ajiukk8qu"/><path class="y_8f2ac4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:braces" /></template>
