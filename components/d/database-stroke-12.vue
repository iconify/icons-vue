<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/l/lwnp_lbfh.css';
import '../../css/b/bzgntubhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><ellipse class="lwnp_lbfh"/><path class="bzgntubhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:database-stroke-12" /></template>
