<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ie3nmnb4k.css';
import '../../css/m/m99yuxjsm.css';
import '../../css/r/rn08x5brb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ie3nmnb4k"/><path class="m99yuxjsm"/><path class="rn08x5brb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bomb-broken" /></template>
