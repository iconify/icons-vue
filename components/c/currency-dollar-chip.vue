<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dcu3-vece.css';
import '../../css/m/mr50r_bjh.css';
import '../../css/f/fzmbgmbjp.css';
import '../../css/u/u_o-feb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dcu3-vece"/><path class="mr50r_bjh"/><path class="fzmbgmbjp"/><path class="u_o-feb_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:currency-dollar-chip" /></template>
