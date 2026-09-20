<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/i78bhubvt.css';
import '../../css/l/lc-1m4bvp.css';
import '../../css/e/e78qg7bkf.css';
import '../../css/k/kros7mbvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="i78bhubvt"/><path class="lc-1m4bvp"/><path class="e78qg7bkf"/><path class="kros7mbvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloudy-moon-broken" /></template>
