<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/p/pzauvpb_u.css';
import '../../css/c/c--u34hmg.css';
import '../../css/l/lq2ydebmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="bi12bsetm"><path class="pzauvpb_u"/><path class="c--u34hmg"/><path class="lq2ydebmf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:battery-75" /></template>
