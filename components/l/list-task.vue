<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/ps43wqbdq.css';
import '../../css/r/r_l-njc4f.css';
import '../../css/l/lbab3mbob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="ps43wqbdq"/><path class="r_l-njc4f"/><path class="lbab3mbob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:list-task" /></template>
