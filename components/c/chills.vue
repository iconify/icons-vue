<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/falrj6b-v.css';
import '../../css/m/m7fafxb8d.css';
import '../../css/d/dxfu67mcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="falrj6b-v"/><path class="m7fafxb8d"/><path clip-rule="evenodd" class="dxfu67mcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chills" /></template>
