<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p4f-2496w.css';
import '../../css/g/g655h3mfp.css';
import '../../css/l/lhsdum_sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":301,"height":201};
const content = `<g class="ft5dv1b6b"><path class="p4f-2496w"/><path class="g655h3mfp"/><path class="lhsdum_sg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cif:cm" /></template>
