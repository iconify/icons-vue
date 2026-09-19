<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a5sbkchck.css';
import '../../css/y/yovjmyyvz.css';
import '../../css/p/p6ivtgb6n.css';
import '../../css/l/l9ft0lwss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="a5sbkchck"/><path clip-rule="evenodd" class="yovjmyyvz"/><path class="p6ivtgb6n"/><path class="l9ft0lwss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:loop-plus-print" /></template>
