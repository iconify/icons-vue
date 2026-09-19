<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pv6pnyb6o.css';
import '../../css/i/icuiavh2e.css';
import '../../css/k/kvxhi2erz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pv6pnyb6o"/><path class="icuiavh2e"/><path class="kvxhi2erz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:invoice-03" /></template>
