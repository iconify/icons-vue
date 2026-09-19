<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o1ewvkqje.css';
import '../../css/v/vvytp-bxb.css';
import '../../css/r/rfbbqhsqc.css';
import '../../css/n/n25-ct7ex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="o1ewvkqje"/><path clip-rule="evenodd" class="vvytp-bxb"/><path clip-rule="evenodd" class="rfbbqhsqc"/><path class="n25-ct7ex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:internet-print" /></template>
