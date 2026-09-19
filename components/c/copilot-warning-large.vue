<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xhuizzi_l.css';
import '../../css/d/djjsp__wh.css';
import '../../css/u/uoqeok1kf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="cuyn6tgcc"><path class="xhuizzi_l"/><path class="djjsp__wh"/><path class="uoqeok1kf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:copilot-warning-large" /></template>
