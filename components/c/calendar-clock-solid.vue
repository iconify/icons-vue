<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/y3rlqzmys.css';
import '../../css/i/i378c-rig.css';
import '../../css/r/rqaq9tbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="y3rlqzmys"/><path class="i378c-rig wm-a"/><path class="rqaq9tbyz wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calendar-clock-solid" /></template>
