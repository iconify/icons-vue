<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gxpqwabxe.css';
import '../../css/m/mn-c1gvts.css';
import '../../css/d/d82kh5btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gxpqwabxe"/><path class="mn-c1gvts"/><path class="d82kh5btl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:business-metaphor-boat-success" /></template>
