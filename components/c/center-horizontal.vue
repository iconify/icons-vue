<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/a/a-wf-ib2y.css';
import '../../css/j/jc6w6-bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a-wf-ib2y"/><rect transform="matrix(-1 0 0 1 15 5.5)" class="jc6w6-bos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:center-horizontal" /></template>
