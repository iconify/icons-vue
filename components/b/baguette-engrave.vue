<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/di6-n2bva.css';
import '../../css/r/ritfql38f.css';
import '../../css/w/wevkxlbtt.css';
import '../../css/f/f545reb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="di6-n2bva wm-k"/><path class="ritfql38f wm-shadow"/><path class="wevkxlbtt wm-k"/><path class="f545reb7b wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:baguette-engrave" /></template>
