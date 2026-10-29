<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/h9c6-6b9c.css';
import '../../css/t/towxrt7ua.css';
import '../../css/h/ho37u6b_q.css';
import '../../css/h/hqkt4rbrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="h9c6-6b9c wm-k"/><path class="towxrt7ua wm-k"/><path class="ho37u6b_q wm-a"/><path class="hqkt4rbrv wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevrons-down-sketch" /></template>
