<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jki9dnbuh.css';
import '../../css/d/dpzqyvzkr.css';
import '../../css/f/f_7mvhbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jki9dnbuh"/><path class="dpzqyvzkr"/><path clip-rule="evenodd" class="f_7mvhbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-warning-outline" /></template>
