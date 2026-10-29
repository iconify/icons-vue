<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xe5z6mstv.css';
import '../../css/y/yab-qjc4s.css';
import '../../css/j/j_co9j11q.css';
import '../../css/d/du_xhybiq.css';
import '../../css/p/pd6es9u_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xe5z6mstv"/><path class="wm-k yab-qjc4s"/><path class="j_co9j11q wm-k"/><path class="du_xhybiq wm-k"/><path class="pd6es9u_u wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-penguin-sketch" /></template>
