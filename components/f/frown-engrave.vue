<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y_dfk98ko.css';
import '../../css/d/ddwgo19qw.css';
import '../../css/y/yw4fz_b6b.css';
import '../../css/u/umu5-_q-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k y_dfk98ko"/><path class="ddwgo19qw wm-shadow"/><path class="wm-k yw4fz_b6b"/><path class="umu5-_q-w wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:frown-engrave" /></template>
