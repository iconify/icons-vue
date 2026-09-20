<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vgynvrhex.css';
import '../../css/l/l34jdmbes.css';
import '../../css/j/jsl6qobau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vgynvrhex"/><path class="l34jdmbes"/><path class="jsl6qobau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:logout-3-broken" /></template>
