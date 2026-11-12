<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0urbhscb.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/n/nt0zokbhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG7MJCveto" x1="43.5" x2="468.5" y1="43.5" y2="468.5" gradientUnits="userSpaceOnUse"><stop offset="0" class="s0urbhscb"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVG7MJCveto)" class="nt0zokbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:koshelf-light" /></template>
