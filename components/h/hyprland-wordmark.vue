<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg1mii81m.css';
import '../../css/a/a2w_u1foi.css';
import '../../css/s/s8g6-c9hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVGY14XrXpy" x1="561.93" x2="561.93" y1="593.85" y2="491.29" gradientTransform="translate(-12.423 -12.742)scale(.1525)" gradientUnits="userSpaceOnUse"><stop offset="0" class="xg1mii81m"/><stop offset="1" class="a2w_u1foi"/></linearGradient></defs><path fill="url(#SVGY14XrXpy)" class="s8g6-c9hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:hyprland-wordmark" /></template>
