<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/u74yizbkg.css';
import '../../css/q/qbep8abwr.css';
import '../../css/m/mholsabzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u74yizbkg"/><path class="qbep8abwr"/><path clip-rule="evenodd" class="mholsabzr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:camera-duotone" /></template>
