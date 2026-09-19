<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/haix9ib8v.css';
import '../../css/d/dcrt2swbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="haix9ib8v"/><path clip-rule="evenodd" class="dcrt2swbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:chlamydia-outline" /></template>
