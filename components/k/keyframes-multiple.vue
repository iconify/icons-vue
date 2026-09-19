<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/c/cgh6afzdr.css';
import '../../css/w/wr3ilibzg.css';
import '../../css/q/qg6wjyjbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cgh6afzdr"/><path class="wr3ilibzg"/><path class="qg6wjyjbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:keyframes-multiple" /></template>
