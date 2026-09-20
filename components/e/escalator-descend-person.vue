<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bmgc78bsz.css';
import '../../css/n/nasjo9_5v.css';
import '../../css/f/f0ly2e3dy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="bmgc78bsz"/><path class="nasjo9_5v"/><path class="f0ly2e3dy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:escalator-descend-person" /></template>
