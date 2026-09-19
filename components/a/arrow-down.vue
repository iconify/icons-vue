<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zlv2tpb4e.css';
import '../../css/z/z3h29obsl.css';
import '../../css/m/m-mcntenk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="zlv2tpb4e"/><path class="z3h29obsl"/><path class="m-mcntenk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:arrow-down" /></template>
