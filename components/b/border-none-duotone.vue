<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bi20ndt2y.css';
import '../../css/m/musq95nnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="bi20ndt2y"/><path class="musq95nnq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-none-duotone" /></template>
