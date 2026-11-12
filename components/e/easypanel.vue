<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzfasvb_b.css';
import '../../css/p/p6fgs4blu.css';
import '../../css/j/jrtb88b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG4BeRjcab" x1="395.3" x2="116.7" y1="14.7" y2="497.3" gradientUnits="userSpaceOnUse"><stop offset="0" class="tzfasvb_b"/><stop offset="1" class="p6fgs4blu"/></linearGradient><path fill="url(#SVG4BeRjcab)" class="jrtb88b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:easypanel" /></template>
