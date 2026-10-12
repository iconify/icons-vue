<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xke_bo0dv.css';
import '../../css/g/g4vvtk_cw.css';
import '../../css/o/osg7x0btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xke_bo0dv"/><path class="g4vvtk_cw"/><path class="osg7x0btl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:earth-duotone" /></template>
