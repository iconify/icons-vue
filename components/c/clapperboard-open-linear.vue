<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l6fn0fb1j.css';
import '../../css/l/ldjg42xkf.css';
import '../../css/q/qsend7bgq.css';
import '../../css/j/jxx7sm5gq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l6fn0fb1j"/><path class="ldjg42xkf"/><path class="qsend7bgq"/><path class="jxx7sm5gq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clapperboard-open-linear" /></template>
