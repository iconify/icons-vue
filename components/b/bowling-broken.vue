<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hhov-gbog.css';
import '../../css/d/dcgw77bis.css';
import '../../css/s/soqsp2xkn.css';
import '../../css/k/ko6o-6b9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle transform="rotate(-90 12 7)" class="hhov-gbog"/><circle transform="rotate(-90 12 12)" class="dcgw77bis"/><path class="soqsp2xkn"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bowling-broken" /></template>
