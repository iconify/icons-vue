<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hjuar3b7p.css';
import '../../css/d/dtoolxbmj.css';
import '../../css/u/urpswfa4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hjuar3b7p"/><path class="dtoolxbmj"/><path class="urpswfa4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-minimalistic-2-linear" /></template>
