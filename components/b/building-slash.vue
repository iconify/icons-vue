<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qpc1jhbbj.css';
import '../../css/z/z_beebviz.css';
import '../../css/v/vs2te2huy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="qpc1jhbbj"/><path class="z_beebviz"/><path class="vs2te2huy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:building-slash" /></template>
