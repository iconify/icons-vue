<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gs_mr7bpp.css';
import '../../css/h/h9uq00g_q.css';
import '../../css/q/qkowx-d8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="gs_mr7bpp"/><path class="h9uq00g_q"/><path class="qkowx-d8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-left-bold" /></template>
