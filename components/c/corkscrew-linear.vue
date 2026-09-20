<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d6yf8nbqe.css';
import '../../css/h/hfjwbrilq.css';
import '../../css/p/pxi4ntbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d6yf8nbqe"/><path class="hfjwbrilq"/><rect transform="rotate(44.97 12.113 1)" class="pxi4ntbrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:corkscrew-linear" /></template>
