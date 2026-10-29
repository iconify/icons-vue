<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/im9aepbpd.css';
import '../../css/j/jmuf37b3b.css';
import '../../css/w/wq4m20bqh.css';
import '../../css/e/ewb4c0zlw.css';
import '../../css/p/pht4mnbru.css';
import '../../css/p/pfp6hfb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="im9aepbpd wm-k"/><path class="jmuf37b3b wm-s"/><path class="wm-shadow wq4m20bqh"/><path class="ewb4c0zlw wm-k"/><path class="pht4mnbru wm-a"/><path class="pfp6hfb3z wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-monster-engrave" /></template>
