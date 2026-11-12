<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tb9i-5hiz.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/i/iycln-b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGjTtJQebW" x1="75" x2="437" y1="75" y2="437" gradientUnits="userSpaceOnUse"><stop offset="0" class="tb9i-5hiz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><circle fill="url(#SVGjTtJQebW)" class="iycln-b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ackee-light" /></template>
