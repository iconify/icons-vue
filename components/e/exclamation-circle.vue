<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/f/fjyp83b4c.css';
import '../../css/u/uscd_gbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fjyp83b4c"/><path class="uscd_gbsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:exclamation-circle" /></template>
