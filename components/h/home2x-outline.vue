<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a1tn6e0wi.css';
import '../../css/o/ozhg_rr4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="a1tn6e0wi"/><path clip-rule="evenodd" class="ozhg_rr4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:home2x-outline" /></template>
