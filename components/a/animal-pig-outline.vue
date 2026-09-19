<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fqgjk-b4m.css';
import '../../css/o/oh3h2lnrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="fqgjk-b4m"/><path clip-rule="evenodd" class="oh3h2lnrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:animal-pig-outline" /></template>
