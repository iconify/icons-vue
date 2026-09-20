<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/ab62pjuns.css';
import '../../css/f/fs60iccsb.css';
import '../../css/u/u00ey8bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ab62pjuns"/><path class="fs60iccsb"/><circle class="u00ey8bps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:graph-new-broken" /></template>
