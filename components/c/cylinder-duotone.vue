<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ucogdbb3g.css';
import '../../css/e/es97pcacw.css';
import '../../css/j/jmpresk-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ucogdbb3g"/><path class="es97pcacw"/><path class="jmpresk-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cylinder-duotone" /></template>
