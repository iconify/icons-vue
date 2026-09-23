<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/e/enjc3_bdq.css';
import '../../css/f/fgezz2bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="enjc3_bdq"/><path class="fgezz2bps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card-sparkles-sharp-fill" /></template>
