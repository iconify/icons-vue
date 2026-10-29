<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vo_7bsbnm.css';
import '../../css/d/dpskx5bja.css';
import '../../css/g/gooo09bjz.css';
import '../../css/y/y30swkuwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vo_7bsbnm"/><path class="dpskx5bja wm-a"/><path class="gooo09bjz wm-k"/><path class="wm-a y30swkuwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lock-keyhole-sketch" /></template>
