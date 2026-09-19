<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jzib17bsz.css';
import '../../css/t/tq0xuccly.css';
import '../../css/i/i6e9c_m2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="jzib17bsz"/><path clip-rule="evenodd" class="tq0xuccly"/><path class="i6e9c_m2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:factory-worker" /></template>
