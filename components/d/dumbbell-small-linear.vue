<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c4811sh4p.css';
import '../../css/l/lxu2bbcju.css';
import '../../css/l/lzi1sccmr.css';
import '../../css/r/rlttj4b8m.css';
import '../../css/m/mh8rzrbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c4811sh4p"/><path class="lxu2bbcju"/><path class="lzi1sccmr"/><path class="rlttj4b8m"/><path class="mh8rzrbvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dumbbell-small-linear" /></template>
