<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ah46elb3h.css';
import '../../css/c/c60tcacvt.css';
import '../../css/d/d8hyaw_-d.css';
import '../../css/k/kj80ggv8d.css';
import '../../css/i/iy-yox1gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ah46elb3h wm-k"/><path class="c60tcacvt wm-a"/><path class="d8hyaw_-d wm-k"/><path class="kj80ggv8d wm-a"/><path class="iy-yox1gu wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:brain-cog-sketch" /></template>
