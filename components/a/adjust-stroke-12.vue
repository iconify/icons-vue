<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/ulnk4ybsa.css';
import '../../css/w/w2-6cebly.css';
import '../../css/t/t2l5vjgzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<g class="h01tyzbfu"><circle class="ulnk4ybsa"/><circle class="w2-6cebly"/><path class="t2l5vjgzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:adjust-stroke-12" /></template>
