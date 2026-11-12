<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x154hvr7k.css';
import '../../css/d/db39vbcar.css';
import '../../css/y/y3dpsii2d.css';
import '../../css/t/tjgbqtbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGOlLIIcGW" x1="256" x2="256" y1="512" gradientUnits="userSpaceOnUse"><stop offset=".006" class="x154hvr7k"/><stop offset="1" class="db39vbcar"/></linearGradient><path fill="url(#SVGOlLIIcGW)" class="y3dpsii2d"/><path class="tjgbqtbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ejabberd" /></template>
