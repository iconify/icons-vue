<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/x161jlf-f.css';
import '../../css/g/g7777bb0y.css';
import '../../css/z/z8cuebffl.css';
import '../../css/x/x-me61blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="x161jlf-f"/><path clip-rule="evenodd" class="g7777bb0y"/><path class="z8cuebffl"/><path clip-rule="evenodd" class="x-me61blo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:cancerous-cell-nuclei" /></template>
