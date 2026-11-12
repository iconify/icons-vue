<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvcjt11dq.css';
import '../../css/s/stqyn-aem.css';
import '../../css/b/ba8nfsfvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGitQdVoSr" x1="-75.6" x2="450" y1="387.8" y2="173" gradientUnits="userSpaceOnUse"><stop offset="0" class="qvcjt11dq"/><stop offset="1" class="stqyn-aem"/></linearGradient><path fill="url(#SVGitQdVoSr)" class="ba8nfsfvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:logto" /></template>
