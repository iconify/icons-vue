<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/y5btkbb_w.css';
import '../../css/p/p53xcyb3q.css';
import '../../css/t/tuoen37fg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="y5btkbb_w"/><path class="p53xcyb3q"/><path class="tuoen37fg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-scatter-bubble-sharp-two-tone" /></template>
