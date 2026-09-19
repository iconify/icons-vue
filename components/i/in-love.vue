<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wc0j0g20c.css';
import '../../css/u/u_mclfbbt.css';
import '../../css/u/ucpkowjmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wc0j0g20c"/><path class="u_mclfbbt"/><path class="ucpkowjmb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:in-love" /></template>
