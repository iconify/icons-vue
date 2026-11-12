<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs666di4s.css';
import '../../css/x/xaigl9buy.css';
import '../../css/k/k0hbd4wrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGeBafsd8k" x1="475.2" x2="33.6" y1="392.2" y2="137.2" gradientUnits="userSpaceOnUse"><stop offset="0" class="gs666di4s"/><stop offset="1" class="xaigl9buy"/></linearGradient><path fill="url(#SVGeBafsd8k)" class="k0hbd4wrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beeper" /></template>
