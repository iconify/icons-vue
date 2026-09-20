<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s6deurbms.css';
import '../../css/s/si_mtzbvj.css';
import '../../css/p/pob85mb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s6deurbms"/><path class="si_mtzbvj"/><path class="pob85mb3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-2x2-broken" /></template>
