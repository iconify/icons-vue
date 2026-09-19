<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vah4cm-_c.css';
import '../../css/j/jky65bbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="vah4cm-_c"/><path clip-rule="evenodd" class="jky65bbnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:graph-scatter" /></template>
