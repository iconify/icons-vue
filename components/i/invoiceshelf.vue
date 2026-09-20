<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1j9atbnx.css';
import '../../css/x/xxyaynvxj.css';
import '../../css/m/mrehdqb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGDFHYcdvA" x1="21.252" x2="490.748" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="d1j9atbnx"/><stop offset="1" class="xxyaynvxj"/></linearGradient><path fill="url(#SVGDFHYcdvA)" class="mrehdqb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:invoiceshelf" /></template>
