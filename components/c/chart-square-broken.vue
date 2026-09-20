<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/ka2lwnn7w.css';
import '../../css/f/f__nic5ty.css';
import '../../css/t/tzz5dibos.css';
import '../../css/s/si_mtzbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ka2lwnn7w"/><path class="f__nic5ty"/><path class="tzz5dibos"/><path class="si_mtzbvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chart-square-broken" /></template>
