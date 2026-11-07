<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/oos2x6mvr.css';
import '../../css/r/rumgkrbdt.css';
import '../../css/j/joig5dakl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oos2x6mvr"/><path class="rumgkrbdt"/><path class="joig5dakl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dialog-broken" /></template>
