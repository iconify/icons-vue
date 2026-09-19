<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/y/y-ahjfb0g.css';
import '../../css/y/ydy6h4gep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><path class="y-ahjfb0g"/><circle class="ydy6h4gep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:at-sign" /></template>
