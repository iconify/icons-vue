<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sv0c39bkq.css';
import '../../css/o/ot_1jemuk.css';
import '../../css/o/ouugfwbdl.css';
import '../../css/w/w99e3fgyw.css';
import '../../css/j/j7-ucebrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><defs><linearGradient id="SVGZpJZGbnW" x1="10" x2="14" y1="5.03" y2="19" gradientUnits="userSpaceOnUse"><stop offset="0" class="sv0c39bkq"/><stop offset=".4" class="sv0c39bkq"/><stop offset="1" class="ot_1jemuk"/></linearGradient></defs><path class="ouugfwbdl wm-k"/><path class="w99e3fgyw wm-deco"/><path fill="url(#SVGZpJZGbnW)" class="j7-ucebrc wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-valentine:chevrons-right" /></template>
