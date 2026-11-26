<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gfhz007bp.css';
import '../../css/w/wgwk4qbzs.css';
import '../../css/x/x5ki7cu8d.css';
import '../../css/b/bdx9oib7f.css';
import '../../css/m/mtjk3naxw.css';
import '../../css/r/rziv8t64q.css';
import '../../css/r/r0l81u2iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><radialGradient id="SVGXFTBEcYO" cx="75.4" cy="100" r="140.8" gradientUnits="userSpaceOnUse"><stop offset="0" class="gfhz007bp"/><stop offset=".85" class="wgwk4qbzs"/><stop offset="1" class="wgwk4qbzs"/></radialGradient></defs><path class="x5ki7cu8d"/><path fill="url(#SVGXFTBEcYO)" transform="matrix(2.5 0 0 2.5 5.148 5.148)" class="bdx9oib7f"/><path class="mtjk3naxw"/><path class="rziv8t64q"/><path class="r0l81u2iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:globe-with-meridians" /></template>
