<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/y/y-hyj2x6a.css';
import '../../css/f/fwl6ucbbe.css';
import '../../css/y/y4mfbjt5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="y-hyj2x6a"/><path class="fwl6ucbbe"/><path class="y4mfbjt5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:camera-automatically-01" /></template>
