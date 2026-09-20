<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/f8hzo4ber.css';
import '../../css/y/y98xg9blh.css';
import '../../css/y/ye_46gv7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="f8hzo4ber"/><path class="y98xg9blh"/><path class="ye_46gv7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:desktop-action-monitor-question" /></template>
