<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umbtk6blu.css';
import '../../css/i/ign-fos0g.css';
import '../../css/c/c90rkqbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGSv0Rxeuw" x1="-544.697" x2="-427.784" y1="677.626" y2="677.626" gradientTransform="matrix(4.3793 0 0 -4.3793 2385.399 3223.534)" gradientUnits="userSpaceOnUse"><stop offset="0" class="umbtk6blu"/><stop offset="1" class="ign-fos0g"/></linearGradient><path fill="url(#SVGSv0Rxeuw)" class="c90rkqbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cooler-control" /></template>
