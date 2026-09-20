<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/fk68dsbja.css';
import '../../css/r/rus1vdoss.css';
import '../../css/s/s1albsb-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fk68dsbja"/><path class="rus1vdoss"/><path class="s1albsb-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:hexagon-3d" /></template>
