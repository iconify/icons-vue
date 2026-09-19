<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hl5setcia.css';
import '../../css/r/rfhv6dwjy.css';
import '../../css/g/g-pa23blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="hl5setcia"/><path class="rfhv6dwjy"/><path class="g-pa23blj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:house-gear-fill" /></template>
