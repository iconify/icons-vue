<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r5c5j4bbq.css';
import '../../css/j/j-czlub9k.css';
import '../../css/p/pdlm26v3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r5c5j4bbq"/><path class="j-czlub9k"/><path class="pdlm26v3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:cleaning-robot-vacuum" /></template>
