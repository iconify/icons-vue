<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/f/f3mi_ybsx.css';
import '../../css/t/t0r8jch9h.css';
import '../../css/h/hky0ybjra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f3mi_ybsx"/><path class="t0r8jch9h"/><path class="hky0ybjra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:file-code-check" /></template>
