<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v10bhlb1p.css';
import '../../css/f/f9o0vpbpo.css';
import '../../css/m/mcrfs6b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v10bhlb1p"/><path class="f9o0vpbpo"/><path class="mcrfs6b7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:insert-pi" /></template>
