<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mivxb5rsc.css';
import '../../css/l/lsklipwzp.css';
import '../../css/l/lihvguq0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<radialGradient id="SVGaLqqLmFI" cx="-703.01" cy="797.671" r=".929" gradientTransform="rotate(89.951 -438255.19 -27352.81)scale(584 -584)" gradientUnits="userSpaceOnUse"><stop offset="0"/><stop offset="1" class="mivxb5rsc"/></radialGradient><path fill="url(#SVGaLqqLmFI)" class="lsklipwzp"/><path class="lihvguq0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:linkwarden" /></template>
