<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz0dcbb8n.css';
import '../../css/a/acpm77yta.css';
import '../../css/n/nln0yoikt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG1UpyudTL" x1="-.095" x2="51244.359" y1="507.833" y2="-49951.543" gradientUnits="userSpaceOnUse"><stop offset="0" class="oz0dcbb8n"/><stop offset="1" class="acpm77yta"/></linearGradient><path fill="url(#SVG1UpyudTL)" class="nln0yoikt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kaunta" /></template>
