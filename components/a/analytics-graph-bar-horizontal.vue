<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r6ez41b0w.css';
import '../../css/v/vm8xudbsl.css';
import '../../css/q/qyf-xkhld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r6ez41b0w"/><path class="vm8xudbsl"/><path class="qyf-xkhld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:analytics-graph-bar-horizontal" /></template>
