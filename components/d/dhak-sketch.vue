<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mc2s-q1px.css';
import '../../css/o/okga0ebte.css';
import '../../css/q/qoj7i61nw.css';
import '../../css/k/k7xullbbh.css';
import '../../css/i/i1jlvbbcb.css';
import '../../css/b/bku8rghaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mc2s-q1px wm-k"/><path class="okga0ebte wm-k"/><path class="qoj7i61nw wm-k"/><path class="k7xullbbh wm-k"/><path class="i1jlvbbcb wm-a"/><path class="bku8rghaj wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:dhak-sketch" /></template>
