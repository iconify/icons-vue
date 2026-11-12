<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz0dcbb8n.css';
import '../../css/a/acpm77yta.css';
import '../../css/e/eh9hibb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGsROPFdNx" x1="-.1" x2="51244.4" y1="507.8" y2="-49951.5" gradientUnits="userSpaceOnUse"><stop offset="0" class="oz0dcbb8n"/><stop offset="1" class="acpm77yta"/></linearGradient><path fill="url(#SVGsROPFdNx)" class="eh9hibb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kaunta" /></template>
