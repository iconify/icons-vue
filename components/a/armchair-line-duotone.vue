<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/irgi_rb-g.css';
import '../../css/k/kwapx1btc.css';
import '../../css/u/uniftz_yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="irgi_rb-g"/><path class="kwapx1btc"/><path class="uniftz_yv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:armchair-line-duotone" /></template>
