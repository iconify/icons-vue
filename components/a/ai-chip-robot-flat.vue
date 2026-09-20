<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/trbccptdc.css';
import '../../css/y/ym_lztb4y.css';
import '../../css/e/ee10sccwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="trbccptdc"/><path class="ym_lztb4y"/><path class="ee10sccwz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:ai-chip-robot-flat" /></template>
