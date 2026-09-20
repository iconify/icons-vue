<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/m390b8qby.css';
import '../../css/x/xjmp9lmjf.css';
import '../../css/h/hnstdmbhp.css';
import '../../css/n/ndq0ugbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="m390b8qby"/><circle class="xjmp9lmjf"/><path class="hnstdmbhp"/><path class="ndq0ugbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-clock-broken" /></template>
