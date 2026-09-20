<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/ykjg-9bfc.css';
import '../../css/d/dgkn91bac.css';
import '../../css/a/aqdbg2upz.css';
import '../../css/k/k-kwsetci.css';
import '../../css/w/wcfaz7lnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ykjg-9bfc"/><path class="dgkn91bac"/><path class="aqdbg2upz"/><path class="k-kwsetci"/><path class="wcfaz7lnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-horizontal-linear" /></template>
