<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/f/f0ca31jqh.css';
import '../../css/z/zmz_fq_6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="f0ca31jqh"/><path class="zmz_fq_6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:chain" /></template>
