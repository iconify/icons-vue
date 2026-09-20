<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f2jbpwb_z.css';
import '../../css/y/ya4v2ogmm.css';
import '../../css/m/mxy6aifea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><ellipse class="f2jbpwb_z"/><path class="ya4v2ogmm"/><path class="mxy6aifea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:golf-line-duotone" /></template>
