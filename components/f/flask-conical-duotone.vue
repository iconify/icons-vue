<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kr7eu_21a.css';
import '../../css/j/j4cz7fbph.css';
import '../../css/m/m8almhbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kr7eu_21a"/><path class="j4cz7fbph"/><path class="m8almhbma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:flask-conical-duotone" /></template>
