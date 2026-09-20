<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/c_j7ak3pd.css';
import '../../css/g/g4q4f6bzj.css';
import '../../css/p/p1_pxob3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="c_j7ak3pd"/><path class="g4q4f6bzj"/><path class="p1_pxob3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:computer-chip-1-flat" /></template>
