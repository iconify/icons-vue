<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i9an4pqeu.css';
import '../../css/q/qpr5s0bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="i9an4pqeu"/><path clip-rule="evenodd" class="qpr5s0bxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-number-6-fill" /></template>
