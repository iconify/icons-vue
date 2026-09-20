<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dv0qcgorm.css';
import '../../css/q/q6f9akifh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="dv0qcgorm"/><path class="q6f9akifh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:500px" /></template>
