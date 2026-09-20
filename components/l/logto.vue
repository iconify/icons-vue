<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvcjt11dq.css';
import '../../css/s/stqyn-aem.css';
import '../../css/b/ba8nfsfvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGHxAmUH9r" x1="-75.602" x2="449.951" y1="665.83" y2="450.986" gradientTransform="translate(0 -278)" gradientUnits="userSpaceOnUse"><stop offset="0" class="qvcjt11dq"/><stop offset="1" class="stqyn-aem"/></linearGradient><path fill="url(#SVGHxAmUH9r)" class="ba8nfsfvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:logto" /></template>
