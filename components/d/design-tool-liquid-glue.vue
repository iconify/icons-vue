<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s1t9m15yr.css';
import '../../css/m/me3i_bcpu.css';
import '../../css/r/r-70unbaw.css';
import '../../css/i/itz0iqxco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="s1t9m15yr"/><path class="me3i_bcpu"/><path class="r-70unbaw"/><path class="itz0iqxco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:design-tool-liquid-glue" /></template>
