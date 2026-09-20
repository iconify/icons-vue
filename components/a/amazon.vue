<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l4pfilrbr.css';
import '../../css/m/mv74flbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-3.5};
const content = `<g class="cuyn6tgcc"><path class="l4pfilrbr"/><path class="mv74flbio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:amazon" /></template>
