<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/yhnqlx3ap.css';
import '../../css/j/jpyjlobuf.css';
import '../../css/o/omi2j1bhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="yhnqlx3ap"/><path class="jpyjlobuf"/><path class="omi2j1bhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-sparkles-sharp-two-tone" /></template>
