<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/us4l7n-bh.css';
import '../../css/v/v4goc3b9j.css';
import '../../css/t/th46yjuif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="us4l7n-bh"/><path class="v4goc3b9j wm-k"/><path class="th46yjuif wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-play-sketch" /></template>
