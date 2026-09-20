<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kzy9852gd.css';
import '../../css/p/pwbssabuq.css';
import '../../css/k/kg_k8zbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kzy9852gd"/><path class="pwbssabuq"/><path class="kg_k8zbim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bottle-linear" /></template>
