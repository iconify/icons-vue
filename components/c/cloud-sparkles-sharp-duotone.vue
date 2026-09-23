<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/r/rq1ab1rwz.css';
import '../../css/z/zwf05wbdd.css';
import '../../css/m/m9umjn1fz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rq1ab1rwz"/><path class="zwf05wbdd"/><path class="m9umjn1fz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-sparkles-sharp-duotone" /></template>
