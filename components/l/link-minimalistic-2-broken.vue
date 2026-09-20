<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/h8gm2tbay.css';
import '../../css/h/hsch2jdsj.css';
import '../../css/s/svy65vbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="h8gm2tbay"/><path class="hsch2jdsj"/><path class="svy65vbai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-minimalistic-2-broken" /></template>
