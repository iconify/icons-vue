<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/s/s0urbhscb.css';
import '../../css/c/cppumpo2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGbSVJPS2c" x1="71.7" x2="440.3" y1="71.7" y2="440.3" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="s0urbhscb"/></linearGradient><path fill="url(#SVGbSVJPS2c)" class="cppumpo2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:foldergram-light" /></template>
