<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kjky4actn.css';
import '../../css/w/wlhoyjbfi.css';
import '../../css/n/n1l2_vbtw.css';
import '../../css/p/ps3m7jb7i.css';
import '../../css/d/docnxfbze.css';
import '../../css/x/x84d-w1gc.css';
import '../../css/i/i4vv6vpoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kjky4actn"/><path class="wlhoyjbfi wm-k"/><path class="n1l2_vbtw wm-a"/><path class="ps3m7jb7i wm-s"/><path class="docnxfbze wm-k"/><path class="wm-a x84d-w1gc"/><path class="i4vv6vpoj wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calendar-clock-sketch" /></template>
