<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/eizdr2f_d.css';
import '../../css/q/qzcstj6ya.css';
import '../../css/v/voplo8xtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="eizdr2f_d"/><path class="qzcstj6ya"/><path class="voplo8xtw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:flip-reflect-up" /></template>
