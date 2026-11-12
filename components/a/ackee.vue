<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud9mscb4f.css';
import '../../css/w/wrc732bfl.css';
import '../../css/i/iycln-b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGkjbDZbNI" x1="75" x2="437" y1="75" y2="437" gradientUnits="userSpaceOnUse"><stop offset="0" class="ud9mscb4f"/><stop offset="1" class="wrc732bfl"/></linearGradient><circle fill="url(#SVGkjbDZbNI)" class="iycln-b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ackee" /></template>
