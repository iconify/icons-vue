<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/awr1zxi0y.css';
import '../../css/d/dh-362btw.css';
import '../../css/u/uniftz_yv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="awr1zxi0y"/><path class="dh-362btw"/><path class="uniftz_yv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:armchair-line-duotone" /></template>
