<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pyln21b0z.css';
import '../../css/p/pzrn709fu.css';
import '../../css/w/wruw12bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pyln21b0z"/><path class="pzrn709fu"/><path clip-rule="evenodd" class="wruw12bjk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:diabetes-measure-outline" /></template>
