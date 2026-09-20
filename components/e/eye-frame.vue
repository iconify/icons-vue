<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/n/nz26n1b5p.css';
import '../../css/g/g1z6mk3_x.css';
import '../../css/c/cw3fst3sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="nz26n1b5p"/><path class="g1z6mk3_x"/><path class="cw3fst3sg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:eye-frame" /></template>
