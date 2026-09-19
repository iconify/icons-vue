<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2vxnblyk.css';
import '../../css/v/vhcyn02em.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<defs><path id="SVGkshJweqs" class="k2vxnblyk"/></defs><path class="vhcyn02em"/><use width="30" height="20" href="#SVGkshJweqs" transform="matrix(71.9991 0 0 72 120 120)"/><use width="30" height="20" href="#SVGkshJweqs" transform="rotate(239.07 133.748 -44.074)scale(23.99992 23.99978)"/><use width="30" height="20" href="#SVGkshJweqs" transform="rotate(-98.11 185.558 -77.035)scale(24 23.9997)"/><use width="30" height="20" href="#SVGkshJweqs" transform="matrix(6.5991 -23.0749 23.0746 6.59919 288 168)"/><use width="30" height="20" href="#SVGkshJweqs" transform="matrix(14.9991 -18.73557 18.73533 14.99929 240 216)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:cn-4x3" /></template>
