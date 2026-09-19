<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sav6x4bmf.css';
import '../../css/d/dw9we3bns.css';
import '../../css/g/g_gp7lgqe.css';
import '../../css/w/wygl0vbrl.css';
import '../../css/r/rimdl7bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGuL2X0cCO" x1="26.791" x2="11.792" y1="28.467" y2="19.855" gradientTransform="translate(-21.334 -18.666)scale(5.33331)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sav6x4bmf"/><stop offset=".918" class="dw9we3bns"/><stop offset="1" class="g_gp7lgqe"/></linearGradient><linearGradient id="SVGY0i8lcxc" x1="5.209" x2="20.208" y1="2.523" y2="11.136" gradientTransform="translate(-21.334 -18.666)scale(5.33331)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sav6x4bmf"/><stop offset=".918" class="dw9we3bns"/><stop offset="1" class="g_gp7lgqe"/></linearGradient></defs><path fill="url(#SVGuL2X0cCO)" class="wygl0vbrl"/><path fill="url(#SVGY0i8lcxc)" class="rimdl7bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:confluence" /></template>
