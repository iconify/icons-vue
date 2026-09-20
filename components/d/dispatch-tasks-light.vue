<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/d/d-llkv2cb.css';
import '../../css/k/k9xc39bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGX1sCedyn" x1="0" x2="512" y1="0" y2="512" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="d-llkv2cb"/></linearGradient><path fill="url(#SVGX1sCedyn)" class="k9xc39bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dispatch-tasks-light" /></template>
