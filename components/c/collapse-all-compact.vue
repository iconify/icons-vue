<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v8z010bwq.css';
import '../../css/k/kpp0gibyb.css';
import '../../css/u/uxu_holod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="cuyn6tgcc"><path class="v8z010bwq"/><path class="kpp0gibyb"/><path clip-rule="evenodd" class="uxu_holod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:collapse-all-compact" /></template>
