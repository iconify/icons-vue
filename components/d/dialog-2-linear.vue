<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/u/uxtlp1b8r.css';
import '../../css/w/w48o_g6he.css';
import '../../css/r/r3i1mebrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uxtlp1b8r"/><path class="w48o_g6he"/><path class="r3i1mebrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dialog-2-linear" /></template>
