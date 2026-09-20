<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/obl4fsbsr.css';
import '../../css/s/shj84utyn.css';
import '../../css/i/ibfi7qbpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="obl4fsbsr"/><path class="shj84utyn"/><path class="ibfi7qbpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:family-baby-change-diaper" /></template>
