<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k_8y6cbed.css';
import '../../css/p/pu97ujszu.css';
import '../../css/d/d7egxzbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k_8y6cbed"/><path class="pu97ujszu"/><path class="d7egxzbrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-charge-broken" /></template>
