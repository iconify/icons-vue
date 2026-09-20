<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpyz49q5o.css';
import '../../css/d/dvf_gvr6i.css';
import '../../css/l/lq-djpb4j.css';
import '../../css/l/l9o29qb_q.css';
import '../../css/h/h3_2q8qzi.css';
import '../../css/y/yodzen-to.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gpyz49q5o"/><g transform="matrix(.7 0 0 .7 10 10)" class="dvf_gvr6i"><path class="lq-djpb4j"/><circle class="l9o29qb_q"/><circle class="h3_2q8qzi"/><circle class="yodzen-to"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-jupyter-open" /></template>
