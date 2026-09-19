<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sic0zt8nz.css';
import '../../css/q/qtlz6ccaa.css';
import '../../css/f/fo8q8bbcg.css';
import '../../css/p/p-c0qbcqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="sic0zt8nz"/><path class="qtlz6ccaa"/><path class="fo8q8bbcg"/><path class="p-c0qbcqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:building-print" /></template>
