<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/p/p53xcyb3q.css';
import '../../css/h/hvs1cebde.css';
import '../../css/r/rrlah7bvq.css';
import '../../css/d/ddqtrn1yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p53xcyb3q"/><path class="hvs1cebde"/><path class="rrlah7bvq"/><path class="ddqtrn1yy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-line-increasing-sparkles-sharp-two-tone" /></template>
