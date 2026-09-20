<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/rv57m5btj.css';
import '../../css/m/m9qep6biy.css';
import '../../css/l/l70hpib7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rv57m5btj"/><path class="m9qep6biy"/><path class="l70hpib7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:icosahedron" /></template>
