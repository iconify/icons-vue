<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gy7_7wa8u.css';
import '../../css/e/e507l5bmm.css';
import '../../css/c/cuo306b5g.css';
import '../../css/t/tzv_rqbov.css';
import '../../css/s/sx44b5bpg.css';
import '../../css/j/jqsa54b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG5EcXvcda" x1="20.474" x2="491.526" y1="258.9" y2="258.9" gradientTransform="matrix(1 0 0 -1 0 514.9)" gradientUnits="userSpaceOnUse"><stop offset="0" class="gy7_7wa8u"/><stop offset="1" class="e507l5bmm"/></linearGradient><path fill="url(#SVG5EcXvcda)" class="cuo306b5g"/><path class="tzv_rqbov"/><path class="sx44b5bpg"/><path class="jqsa54b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calico" /></template>
