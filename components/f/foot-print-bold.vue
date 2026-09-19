<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r3j7pccxy.css';
import '../../css/t/t-ctftbys.css';
import '../../css/w/wfa4t_zlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r3j7pccxy"/><path class="t-ctftbys"/><path class="wfa4t_zlf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:foot-print-bold" /></template>
