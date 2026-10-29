<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lejs0z4jr.css';
import '../../css/w/wv49vd4-b.css';
import '../../css/g/g4j9ehvsu.css';
import '../../css/q/q3ug9bckq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lejs0z4jr"/><path class="wm-a wv49vd4-b"/><path class="g4j9ehvsu wm-k"/><path class="q3ug9bckq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clock-sketch" /></template>
