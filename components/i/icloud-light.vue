<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/t/tb9i-5hiz.css';
import '../../css/a/ald9c1bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGptwN3cVN" x1="8151.554" x2="2841.913" y1="-5021.914" y2="-4948.677" gradientTransform="matrix(.09676 0 0 -.09676 -274.314 -225.56)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="tb9i-5hiz"/></linearGradient><path fill="url(#SVGptwN3cVN)" class="ald9c1bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:icloud-light" /></template>
