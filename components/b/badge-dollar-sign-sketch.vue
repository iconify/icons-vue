<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/ymm2nhd-k.css';
import '../../css/m/m6g9ed77n.css';
import '../../css/r/ri15-6vbx.css';
import '../../css/m/mkbyrcbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ymm2nhd-k"/><path class="m6g9ed77n wm-a"/><path class="ri15-6vbx wm-k"/><path class="mkbyrcbue wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:badge-dollar-sign-sketch" /></template>
