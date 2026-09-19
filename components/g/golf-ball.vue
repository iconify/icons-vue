<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kk-2hwbmm.css';
import '../../css/w/wkn46nb_i.css';
import '../../css/g/gf3fkwbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="kk-2hwbmm"/><path class="wkn46nb_i"/><path class="gf3fkwbky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:golf-ball" /></template>
