<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/t9im77xci.css';
import '../../css/p/p0til8bxh.css';
import '../../css/z/zjapeywkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t9im77xci"/><path clip-rule="evenodd" class="p0til8bxh"/><path class="zjapeywkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:card-receive-duotone" /></template>
