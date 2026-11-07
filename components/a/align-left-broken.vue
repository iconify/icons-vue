<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hb2atdblt.css';
import '../../css/r/rns374uuw.css';
import '../../css/o/ou2j_7qjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hb2atdblt"/><path class="rns374uuw"/><path class="ou2j_7qjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-left-broken" /></template>
