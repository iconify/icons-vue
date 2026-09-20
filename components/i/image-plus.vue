<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f8le2jbey.css';
import '../../css/o/ol5--vb1y.css';
import '../../css/t/t10685b9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f8le2jbey"/><path clip-rule="evenodd" class="ol5--vb1y"/><path class="t10685b9q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:image-plus" /></template>
