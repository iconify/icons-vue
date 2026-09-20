<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zw5ivtbwu.css';
import '../../css/q/q0bb-wb9a.css';
import '../../css/j/j1187el2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zw5ivtbwu"/><path class="q0bb-wb9a"/><path class="j1187el2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:computer-chip-2-flat" /></template>
