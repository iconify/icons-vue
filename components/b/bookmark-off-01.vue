<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c09dqbc_g.css';
import '../../css/m/mzappkblu.css';
import '../../css/v/vivgit4ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c09dqbc_g"/><path class="mzappkblu"/><path class="vivgit4ai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bookmark-off-01" /></template>
