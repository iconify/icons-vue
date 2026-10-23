<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r5brfdchu.css';
import '../../css/j/jrp2xebmc.css';
import '../../css/g/gx35_lbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r5brfdchu"/><path class="jrp2xebmc"/><path class="gx35_lbkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-chevrons-left-duotone" /></template>
