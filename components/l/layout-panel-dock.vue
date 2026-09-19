<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/be63dc_2z.css';
import '../../css/r/rr-xm1bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="be63dc_2z"/><path clip-rule="evenodd" class="rr-xm1bpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:layout-panel-dock" /></template>
