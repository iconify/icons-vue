<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gutru8b1o.css';
import '../../css/i/icxgbob2x.css';
import '../../css/v/vbkqrsxxc.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n9dtqrb_z.css';
import '../../css/o/olsil3zor.css';
import '../../css/g/gb7ksbbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gutru8b1o"><path class="icxgbob2x"><animate fill="freeze" attributeName="stroke-dashoffset" dur="0.2s" values="4;0"/></path><path fill-opacity="0" stroke-dashoffset="30" class="vbkqrsxxc"><animate fill="freeze" attributeName="stroke-dashoffset" begin="0.2s" dur="0.4s" to="0"/><animate fill="freeze" attributeName="fill-opacity" begin="1.3s" dur="0.15s" to=".3"/></path><g class="ft5dv1b6b"><path stroke-dashoffset="10" class="n9dtqrb_z"><animate fill="freeze" attributeName="stroke-dashoffset" begin="0.7s" dur="0.2s" to="0"/></path><path stroke-dashoffset="6" class="olsil3zor"><animate fill="freeze" attributeName="stroke-dashoffset" begin="0.9s" dur="0.2s" to="0"/></path><path stroke-dashoffset="4" class="gb7ksbbiw"><animate fill="freeze" attributeName="stroke-dashoffset" begin="1.1s" dur="0.2s" to="0"/></path></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:bell-twotone-alert" /></template>
