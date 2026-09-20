<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tbfod3hgq.css';
import '../../css/v/vy_2r-zvg.css';
import '../../css/h/hmq76m6xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><rect class="tbfod3hgq"/><path class="vy_2r-zvg"/><path class="hmq76m6xr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dashboard-chart-arrow" /></template>
