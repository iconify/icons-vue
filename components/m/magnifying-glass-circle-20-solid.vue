<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/ylb1x-b8r.css';
import '../../css/a/aac2bvy1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ylb1x-b8r"/><path clip-rule="evenodd" class="aac2bvy1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:magnifying-glass-circle-20-solid" /></template>
