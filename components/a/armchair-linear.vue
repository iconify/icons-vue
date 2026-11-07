<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dh-362btw.css';
import '../../css/c/c2ccr1cfe.css';
import '../../css/h/hvt2a6e9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dh-362btw"/><path class="c2ccr1cfe"/><path class="hvt2a6e9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:armchair-linear" /></template>
