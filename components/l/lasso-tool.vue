<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/g/gdvdupecv.css';
import '../../css/w/wxxx193iv.css';
import '../../css/o/ogpl226vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2000,"height":2000};
const content = `<g class="h01tyzbfu"><path class="gdvdupecv"/><path class="wxxx193iv"/><path class="ogpl226vk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:lasso-tool" /></template>
