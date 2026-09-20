<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vrr0_dbgw.css';
import '../../css/i/i3tmlwbvp.css';
import '../../css/p/pbcwo2bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vrr0_dbgw"/><path class="i3tmlwbvp"/><path class="pbcwo2bql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:devices-broken" /></template>
