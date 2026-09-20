<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zd0m0mb-d.css';
import '../../css/w/w8w_x3b_q.css';
import '../../css/g/g_uchrbqa.css';
import '../../css/y/yqmcgtbgo.css';
import '../../css/b/bxk-1qbua.css';
import '../../css/o/owjfqrb6d.css';
import '../../css/r/rpvb-o6bq.css';
import '../../css/m/mwws-3jhw.css';
import '../../css/j/jl1wzobvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="zd0m0mb-d"/><path class="w8w_x3b_q"/><path class="g_uchrbqa"/><path class="yqmcgtbgo"/><path class="bxk-1qbua"/><path class="owjfqrb6d"/><g class="rpvb-o6bq"><path class="mwws-3jhw"/><path class="jl1wzobvi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:atm-sign" /></template>
