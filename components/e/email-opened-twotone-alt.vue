<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0avh7b2d.css';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/lft_xobhr.css';
import '../../css/k/km4ml9bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path fill-opacity="0" class="d0avh7b2d"><animate fill="freeze" attributeName="fill-opacity" begin="0.9s" dur="0.15s" to=".3"/></path><g class="nrj6p8qat"><path class="lft_xobhr"><animate fill="freeze" attributeName="stroke-dashoffset" dur="0.6s" values="64;0"/></path><path stroke-dashoffset="24" class="km4ml9bdp"><animate fill="freeze" attributeName="stroke-dashoffset" begin="0.6s" dur="0.3s" to="0"/></path></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:email-opened-twotone-alt" /></template>
