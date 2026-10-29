<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/q/q2dc5gbln.css';
import '../../css/q/qpzntcg6x.css';
import '../../css/a/aalr8-b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="q2dc5gbln"/><path class="qpzntcg6x wm-a"/><path class="aalr8-b6s wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:alarm-clock-off-solid" /></template>
