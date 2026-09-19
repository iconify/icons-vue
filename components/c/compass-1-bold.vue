<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jwztj5b9y.css';
import '../../css/r/r0ghptbtp.css';
import '../../css/y/ynwa9-bwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jwztj5b9y"/><path clip-rule="evenodd" class="r0ghptbtp"/><path class="ynwa9-bwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:compass-1-bold" /></template>
