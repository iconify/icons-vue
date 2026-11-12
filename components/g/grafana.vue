<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mad_2hbbu.css';
import '../../css/e/eoy1so5qh.css';
import '../../css/h/h9250idgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGx3KOLdgt" x1="256" x2="256" y1="153" y2="508.3" gradientUnits="userSpaceOnUse"><stop offset="0" class="mad_2hbbu"/><stop offset="1" class="eoy1so5qh"/></linearGradient><path fill="url(#SVGx3KOLdgt)" class="h9250idgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grafana" /></template>
