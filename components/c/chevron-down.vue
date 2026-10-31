<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sv0c39bkq.css';
import '../../css/o/ot_1jemuk.css';
import '../../css/s/s9c09sbtn.css';
import '../../css/h/hu03yxb5r.css';
import '../../css/e/e9hngit4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><defs><linearGradient id="SVG0YizTdVm" x1="10.01" x2="14.01" y1="8" y2="16" gradientUnits="userSpaceOnUse"><stop offset="0" class="sv0c39bkq"/><stop offset=".4" class="sv0c39bkq"/><stop offset="1" class="ot_1jemuk"/></linearGradient></defs><path class="s9c09sbtn wm-k"/><path class="hu03yxb5r wm-deco"/><path fill="url(#SVG0YizTdVm)" class="e9hngit4q wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-valentine:chevron-down" /></template>
