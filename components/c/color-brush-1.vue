<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/i-8ankb1q.css';
import '../../css/v/v_juk5ico.css';
import '../../css/z/zx3h_acia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="i-8ankb1q"/><path class="v_juk5ico"/><path class="zx3h_acia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:color-brush-1" /></template>
