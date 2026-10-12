<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v6_r5ub0p.css';
import '../../css/v/v9h7snvir.css';
import '../../css/d/dtw45jbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v6_r5ub0p"/><path class="v9h7snvir"/><path class="dtw45jbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:drill-duotone" /></template>
