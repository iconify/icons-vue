<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xr0-4kb2q.css';
import '../../css/y/ypyppybok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="cuyn6tgcc"><path class="xr0-4kb2q"/><path class="ypyppybok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:copilot-large" /></template>
