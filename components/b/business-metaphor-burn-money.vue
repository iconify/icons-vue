<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/f/fftbt4ikp.css';
import '../../css/z/zuqwdabeh.css';
import '../../css/w/wptgjib0k.css';
import '../../css/j/jo5vtjbfe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="fftbt4ikp"/><path class="zuqwdabeh"/><path class="wptgjib0k"/><path class="jo5vtjbfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:business-metaphor-burn-money" /></template>
