<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gezqzx40e.css';
import '../../css/i/ilntfmbad.css';
import '../../css/l/lxiabl_as.css';
import '../../css/u/u7n5henwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGA00xgeiq" x1="202.2" x2="1672.6" y1="271.3" y2="1120.2" gradientUnits="userSpaceOnUse"><stop offset="0" class="gezqzx40e"/><stop offset="1" class="ilntfmbad"/></linearGradient><path fill="url(#SVGA00xgeiq)" class="lxiabl_as"/><linearGradient id="SVG1kCaQd4Y" x1="176.9" x2="1647.3" y1="303" y2="1152" gradientUnits="userSpaceOnUse"><stop offset="0" class="gezqzx40e"/><stop offset="1" class="ilntfmbad"/></linearGradient><path fill="url(#SVG1kCaQd4Y)" class="u7n5henwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fladder" /></template>
