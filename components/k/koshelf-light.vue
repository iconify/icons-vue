<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0urbhscb.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/n/nt0zokbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGWNAuTddA" x1="43.505" x2="468.495" y1="43.505" y2="468.495" gradientUnits="userSpaceOnUse"><stop offset="0" class="s0urbhscb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGWNAuTddA)" class="nt0zokbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:koshelf-light" /></template>
