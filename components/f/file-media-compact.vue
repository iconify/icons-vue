<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hsw04lgqz.css';
import '../../css/q/qviu0dxdv.css';
import '../../css/m/mm1rimbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><path class="hsw04lgqz"/><path clip-rule="evenodd" class="qviu0dxdv"/><path clip-rule="evenodd" class="mm1rimbuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:file-media-compact" /></template>
