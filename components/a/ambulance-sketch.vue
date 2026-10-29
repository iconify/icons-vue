<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kqtbwreef.css';
import '../../css/y/y5ibkwb3c.css';
import '../../css/i/ixkdbb2ly.css';
import '../../css/p/p5j8ju-6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kqtbwreef"/><path class="wm-a y5ibkwb3c"/><path class="ixkdbb2ly wm-k"/><path class="p5j8ju-6f wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ambulance-sketch" /></template>
