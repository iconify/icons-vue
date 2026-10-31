<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oi2c1yfan.css';
import '../../css/o/oi9gvkbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":300,"height":216};
const content = `<g class="ft5dv1b6b"><path class="oi2c1yfan"/><path class="oi9gvkbqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:al" /></template>
