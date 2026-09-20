<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/zv1da0btv.css';
import '../../css/p/p4ymsz41h.css';
import '../../css/k/kuyexsk0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="zv1da0btv"/><path class="p4ymsz41h"/><path class="kuyexsk0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:desktop-action-monitor-add" /></template>
