<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xs1p5p0xc.css';
import '../../css/u/uf50r_q1t.css';
import '../../css/d/d20c2gbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xs1p5p0xc"/><path class="uf50r_q1t"/><path clip-rule="evenodd" class="d20c2gbds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:face-frowning" /></template>
