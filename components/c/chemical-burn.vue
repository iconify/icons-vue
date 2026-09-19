<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d0nqyubyr.css';
import '../../css/e/e06raxbxf.css';
import '../../css/j/jcn5sbflp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="d0nqyubyr"/><path clip-rule="evenodd" class="e06raxbxf"/><path class="jcn5sbflp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chemical-burn" /></template>
