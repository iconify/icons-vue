<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u00_rtbnv.css';
import '../../css/n/n14y29_sm.css';
import '../../css/j/j4y2ez72j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u00_rtbnv"/><path class="n14y29_sm"/><path class="j4y2ez72j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:egg-fried-duotone" /></template>
