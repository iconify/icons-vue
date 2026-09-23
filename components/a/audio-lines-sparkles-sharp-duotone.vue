<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/h/hb0q4-uhx.css';
import '../../css/h/h8a5dda0k.css';
import '../../css/i/ik2waybte.css';
import '../../css/h/hdhpu_gyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hb0q4-uhx"/><path class="h8a5dda0k"/><path class="ik2waybte"/><path class="hdhpu_gyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:audio-lines-sparkles-sharp-duotone" /></template>
